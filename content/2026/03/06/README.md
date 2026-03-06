# Awesome List Updates on Mar 06, 2026

13 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome V](/content/vlang/awesome-v/README.md)

### Command-line

*   [dnshammer (⭐0)](https://github.com/tailsmails/dnshammer) - A covert communication channel that encodes data into DNS cache timing differences.

## [2. Awesome Cpp](/content/fffaraz/awesome-cpp/README.md)

### Networking

*   [OpenDDS (⭐1.5k)](https://github.com/objectcomputing/OpenDDS) - An open source C++ implementation of the Object Management Group (OMG) Data Distribution Service (DDS). \[Apache2]

### Miscellaneous

*   [Gear-Lib (⭐3.2k)](https://github.com/gozfree/gear-lib) - A collection of basic libraries in POSIX C for embedded and network service development. \[MIT]
*   [single\_file\_libs (⭐9.8k)](https://github.com/r-lyeh/single_file_libs) - C/C++ open-source libraries with minimal dependencies. \[Various]

## [3. Awesome Lit](/content/web-padawan/awesome-lit/README.md)

### Extensions

*   [`@tanstack/lit-table`](https://tanstack.com/table/latest/docs/framework/lit/lit-table) - Headless UI for building powerful tables & datagrids with Lit.

## [4. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### Code Runner / Quickfix

*   [mikeboiko/nvim-flow (⭐3)](https://github.com/mikeboiko/nvim-flow) - File-scoped command runner with YAML configuration, command preview, debug integration, and traceback quickfix.

## [5. Htaccess](/content/phanan/htaccess/README.md)

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

## [6. Awesome Cli Apps in a Csv](/content/toolleeo/awesome-cli-apps-in-a-csv/README.md)

### Clean up of files and directories

*   [NTC](https://codeberg.org/ItsZariep/ntc) - A program that, based on the contents of a folder, create tabs (subfolders inside the selected folder) and displays their contents.

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

### Networking

*   [Thymus](https://github.com/blademd/thymus) - An interactive browser & editor for network configuration files.

## [7. Awesome Testing](/content/TheJambo/awesome-testing/README.md)

### Software / Visual Testing

*   [Frostbyte Screenshot Action (⭐0)](https://github.com/OzorOwn/frostbyte-screenshot-action) - GitHub Action for automated website screenshots in CI/CD pipelines. Supports multiple viewports, full-page capture, and dark mode emulation.

## [8. Awesome Zig](/content/zigcc/awesome-zig/README.md)

### Language Essentials / String Processing

*   [atman/zg](https://codeberg.org/atman/zg) - Provides Unicode text processing for Zig projects. It works correctly with the Russian language and other languages.

## [9. Awesome Go](/content/avelino/awesome-go/README.md)

### Artificial Intelligence

*   [hotplex (⭐7)](https://github.com/hrygo/hotplex) - AI Agent runtime engine with long-lived sessions for Claude Code, OpenCode, pi-mono and other CLI AI tools. Provides full-duplex streaming, multi-platform integrations, and secure sandbox.

### Advanced Console UIs

*   [phoenix (⭐17)](https://github.com/phoenix-tui/phoenix) - High-performance TUI framework with Elm-inspired architecture, perfect Unicode rendering, and zero-allocation event system.

### SQL Query Builders

*   [relica (⭐7)](https://github.com/coregx/relica) - Type-safe database query builder with zero production dependencies, LRU statement cache, batch operations, and support for JOINs, subqueries, CTEs, and window functions.

### Job Scheduler

*   [pending (⭐3)](https://github.com/kahoon/pending) - ID-based debounced task scheduler for deferred tasks with cancellation, graceful shutdown, and optional concurrency limits.

### Routers / Libraries for creating HTTP middlewares

*   [fursy (⭐1)](https://github.com/coregx/fursy) - HTTP router with type-safe generic handlers, automatic OpenAPI 3.1 generation from code, and RFC 9457 error responses.

## [10. Awesome Rust](/content/rust-unofficial/awesome-rust/README.md)

### Applications

*   [temps (⭐225)](https://github.com/gotempsh/temps) - A self-hosted PaaS that replaces Vercel, analytics, error tracking, and uptime monitoring with a single Rust binary

### Applications / Database

*   [sabiql (⭐124)](https://github.com/riii111/sabiql) \[[sabiql](https://crates.io/crates/sabiql)] - A fast, driver-less TUI to browse, query, and edit PostgreSQL databases. [![CI](https://github.com/riii111/sabiql/actions/workflows/ci.yml/badge.svg)](https://github.com/riii111/sabiql/actions/workflows/ci.yml)

### Applications / Productivity

*   [max-sixty/worktrunk (⭐2.8k)](https://github.com/max-sixty/worktrunk) \[[worktrunk](https://crates.io/crates/worktrunk)] - CLI for git worktree management designed for running AI agents in parallel, with hooks, LLM commit messages, and merge workflows [![CI](https://img.shields.io/github/actions/workflow/status/max-sixty/worktrunk/ci.yaml?branch=main\&logo=github)](https://github.com/max-sixty/worktrunk/actions?query=branch%3Amain+workflow%3Aci)

## [11. Awesome Mac](/content/jaywcjlove/awesome-mac/README.md)

### Reading and Writing Tools / Note-taking

*   [Zettel (⭐48)](https://github.com/AlexW00/Zettel) - Minimal, distraction-free note-taking app with Markdown and hashtag-based organization. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/AlexW00/Zettel) [![App Store](https://jaywcjlove.github.io/sb/ico/min-app-store.svg "App Store Software")](https://apps.apple.com/app/zettel-quick-notes/id6748525244?platform=mac)

## [12. Typedb Awesome](/content/vaticle/typedb-awesome/README.md)

### Open source projects using TypeDB

*   [`go-typeql`](https://github.com/CaliLuke/go-typeql) - A Go ORM for TypeDB 3.x with type-safe CRUD, query building, migrations, and code generation.
*   [`skills`](https://github.com/CaliLuke/skills) - A collection of agent skills, including a TypeDB skill for agent workflows.

## [13. Awesome Datascience](/content/academic/awesome-datascience/README.md)

### Tools

*   [Frostbyte MCP (⭐0)](https://github.com/OzorOwn/frostbyte-mcp) - MCP server providing 13 data tools for AI agents: real-time crypto prices, IP geolocation, DNS lookups, web scraping to markdown, code execution, and screenshots. One API key for 40+ services.

---

- Next: [Mar 05, 2026](/content/2026/03/05/README.md)