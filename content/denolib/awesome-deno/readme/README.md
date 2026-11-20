# Awesome Deno Overview

Curated list of awesome things related to Deno

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/denolib/awesome-deno/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 denolib/awesome-deno](https://github.com/denolib/awesome-deno) · ⭐ 4.4K · 🏷️ Platforms

[ [Daily](/content/denolib/awesome-deno/README.md) / [Weekly](/content/denolib/awesome-deno/week/README.md) / Overview ]

---

# Awesome Deno [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://github.com/denolib/awesome-deno/raw/main/deno-logo.png" align="right" width="100">](https://deno.land)

Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

This list is a collection of the best Deno modules and resources.

## Contents

*   [Docs](#docs)
    *   [Official Docs](#official-docs)
    *   [External Docs](#external-docs)
*   [Modules](#modules)
    *   [Automation](#automation)
    *   [CLI utils](#cli-utils)
    *   [Cloud APIs](#cloud-apis)
    *   [Database](#database)
    *   [Editor framework](#editor-framework)
    *   [Frontend framework](#frontend-framework)
    *   [Game engine](#game-engine)
    *   [Logging](#logging)
    *   [Mail](#mail)
    *   [Markdown](#markdown)
    *   [Static site generator](#static-site-generator)
    *   [Social Platform APIs](#social-platform-apis)
    *   [Template engine](#template-engine)
    *   [Testing](#testing)
    *   [Utils](#utils)
    *   [Web framework](#web-framework)
    *   [Web utils](#web-utils)
    *   [Webview](#webview)
*   [Registries](#registries)
*   [Showcases](#showcases)
*   [Tools](#tools)
*   [Integrations](#integrations)
*   [Articles](#articles)
*   [Blogs/Newsletters](#blogsnewsletters)
*   [Presentations](#presentations)
*   [Resources](#resources)
    *   [Books](#books)
*   [Resources in Other Languages](#resources-in-other-languages)
    *   [Chinese](#chinese)
    *   [Hebrew](#hebrew)
    *   [Indonesian](#indonesian)
    *   [Italian](#italian)
    *   [Japanese](#japanese)
    *   [Russian](#russian)
    *   [Spanish](#spanish)
    *   [Darija (Arabe marocain)](#darija)
    *   [Kurdish (Central)](#kurdish-central)

## Docs

### Official Docs

*   [Deno API Reference](https://docs.deno.com/api)
*   [Deno Manual](https://docs.deno.com)
*   [Deno Standard Library](https://jsr.io/@std)
*   [Official Site](https://deno.com)

### External Docs

*   [V8 Docs for Deno](https://denolib.github.io/v8-docs/)

## Modules

### Automation

*   [zuke (⭐47)](https://github.com/zuke-build/zuke) - Code-first, strongly-typed build automation system where builds are defined as TypeScript classes.

### CLI utils

*   [cac (⭐3.1k)](https://github.com/cacjs/cac) - Simple yet powerful framework for building command-line apps.
*   [cli-spinner (⭐57)](https://github.com/ameerthehacker/deno-cli-spinners) - Show spinners in the terminal while running long tasks.
*   [cliffy (⭐1.2k)](https://github.com/c4spar/cliffy) - The complete solution for building interactive command-line tools.
*   [clinfer (⭐10)](https://github.com/jersou/clinfer) - Automatically generate CLIs from JS objects, classes or ES modules.
*   [commit-sage-cli (⭐62)](https://github.com/AhmedOsman101/commit-sage-cli) - Generates Conventional Commit messages with AI based on Git repository changes.
*   [yargs (⭐12k)](https://github.com/yargs/yargs) - The modern, pirate-themed successor to optimist.

### Cloud APIs

*   [aws-api](https://aws-api.danopia.deno.net/) - From-scratch Typescript AWS API client built for Deno.
*   [sigflint (⭐2)](https://github.com/bompus/sigflint) - AWS Signature Version 4 and SigV4a request signing with no dependencies, for use with `fetch`.

### Database

*   [@iuioiua/redis](https://jsr.io/@iuioiua/redis) - Fast, lightweight Redis client built upon the Web Streams API.
*   [deno\_mongo (⭐512)](https://github.com/denodrivers/mongo) - MongoDB database driver.
*   [kvdock (⭐4)](https://github.com/zisam-glitch/kvdock) - Zero-dependency key-value and multi-tier caching engine with native Deno KV support and single-flight stampede protection.
*   [maxminddb (⭐18)](https://github.com/josh-hemphill/maxminddb-wasm) - A library that enables the usage of MaxmindDB geoIP database files
*   [nessie (⭐519)](https://github.com/lmxrd/deno-nessie) - Create, migrate and rollback migrations for PostgreSQL, MySQL and SQLite.
*   [postgres (⭐653)](https://github.com/denodrivers/postgres) - Driver for PostgreSQL database.
*   [redis (⭐464)](https://github.com/denodrivers/redis) - An experimental implementation of redis client for deno.

### Editor framework

*   [Denops (⭐794)](https://github.com/vim-denops/denops.vim) - 🐜 An ecosystem to write Vim/Neovim plugins with Deno.

### Frontend framework

*   [fresh (⭐14k)](https://github.com/freshframework/fresh) - The next-gen web framework.

### Game engine

*   [caviar (⭐172)](https://github.com/load1n9/caviar) - ⚡ Blazing fast, modern, Game Engine powered by WebGPU for Deno and the browser
*   [sdl2 (⭐184)](https://github.com/littledivy/deno_sdl2) - SDL2 module for Deno

### Image

*   [aigifmaker (⭐0)](https://github.com/hanshs474/aigifmaker-ts) - Turn text prompts into animated GIFs with the AI GIF Maker API.
*   [ImageScript (⭐685)](https://github.com/imagescript/ImageScript) - Image processing in JavaScript, utilizing WebAssembly for performance.
*   [kavel (⭐2)](https://github.com/hanshs474/kavel-ts) - Generate and edit images with AI without an API key or account.

### Logging

*   [LogTape (⭐2k)](https://github.com/dahlia/logtape) - Simple logging library with zero dependencies for Deno/Node.js/Bun/browsers.

### Mail

*   [dmarc-rua (⭐2)](https://github.com/domaincanary/dmarc-rua) - Parse DMARC aggregate reports from XML, gzip, zip and report emails.

### Markdown

*   [LiteMarkup (⭐2)](https://github.com/tuures/LiteMarkup) - AST-first parser. Under 3 KB gzipped, zero dependencies.

### Static site generator

*   [lume (⭐2.3k)](https://github.com/lumeland/lume) - A static site generator similar to Jekyll or Eleventy with support for multiple file formats.
*   [zerho (⭐1)](https://github.com/glastor-core/zerho) - High-performance documentation engine for Deno 2 and Edge runtimes with interactive playground, OpenAPI explorer, and native llms.txt support.

### Social Platform APIs

*   [Circe (⭐1)](https://github.com/sxnnyside-project/circe) - Inversion-of-control framework for discord.js bots with file-system routing, guards and Gateway or HTTP transport.
*   [discordeno (⭐938)](https://github.com/discordeno/discordeno) - Discord API library for Deno
*   [grammY (⭐3.8k)](https://github.com/grammyjs/grammY) - Telegram Bot API framework for Deno.
*   [MTKruto (⭐175)](https://github.com/MTKruto/MTKruto) - Deno-first, cross-runtime client library for Telegram's MTProto API.

### Template engine

*   [eta (⭐1.8k)](https://github.com/bgub/eta) - Fast, lightweight, and configurable embedded template engine.

### Testing

*   [keploy (⭐20k)](https://github.com/keploy/keploy) - Record real traffic to generate integration tests and mock Postgres, Redis, and fetch calls.
*   [qunitx (⭐36)](https://github.com/izelnakri/qunitx) - Zero dependency, fully customizable, mature, universal test API that can run interchangably in node.js, Deno & browser, using default runtime test runners.
*   [superdeno (⭐123)](https://github.com/cmorten/superdeno) - Super-agent driven library for testing Deno HTTP servers.
*   [tepi (⭐6)](https://github.com/jupegarnica/tepi) - A .http Test Runner
*   [unexpected (⭐367)](https://github.com/unexpectedjs/unexpected) - Extensible BDD assertion toolkit.

### Utils

*   [computed\_types (⭐358)](https://github.com/neuledge/computed-types) - Joi like validators for Typescript and Deno.
*   [croner (⭐2.6k)](https://github.com/Hexagon/croner) - Cron library with advanced scheduling features, well-documented API, and zero dependencies.
*   [csv-pipe (⭐15)](https://github.com/martsinlabs/csv-pipe) - Typed, zero-dependency CSV parser and encoder for every runtime.
*   [deno\_kv\_fs (⭐16)](https://github.com/hviana/deno_kv_fs) Deno KV file system, compatible with Deno deploy. Makes use of Web Streams API.
*   [durationjs (⭐21)](https://github.com/retraigo/duration.js) - Get formatted time duration from a timestamp or a human-readable string.
*   [envapt (⭐25)](https://github.com/materwelonDhruv/envapt) - Read environment variables as typed values with built-in converters, Standard Schema validation, and zero dependencies.
*   [esm-itter (⭐3)](https://github.com/tillsanders/esm-itter) – A strongly typed fork of the popular EventEmitter3 with a focus on EcmaScript module syntax, TypeScript and modern tooling.
*   [evt (⭐460)](https://github.com/garronej/evt) - Type safe replacement for EventEmitter.
*   [fastest-validator (⭐1.5k)](https://github.com/icebob/fastest-validator) - Schema validator for all javascript platforms
*   [fortuna (⭐21)](https://github.com/retraigo/fortuna) - Weighted gacha system.
*   [injecute (⭐5)](https://github.com/Masyaka/injecute) - Type-safe dependency injection container with explicit wiring and no decorators.
*   [json-schema-for-llms (⭐1)](https://github.com/carmenaresearch/json-schema-for-llms) - Turn a JSON document too large for an LLM context window into a short JSON Schema with counts, ranges and example records.
*   [optionals (⭐193)](https://github.com/OliverBrotchie/optionals) - Rust-like error handling and options with exhaustive pattern matching.
*   [PLS (⭐9)](https://github.com/xorgram/pls) - Use 2 lines to persist localStorage in any database, including, but not limited to, MongoDB, PostgreSQL and Redis.
*   [qrcode (⭐47)](https://github.com/denorg/qrcode) - QR code image generator for Deno.
*   [rubico (⭐283)](https://github.com/a-synchronous/rubico) - 🏞 \[a]synchronous function composition; it just works.
*   [solc (⭐72)](https://github.com/deno-web3/solc) - 💎 Solidity bindings for Deno.
*   [switcher4deno (⭐2)](https://github.com/switcherapi/switcher-client-deno) - Feature Flag Deno SDK client for Switcher-API.
*   [wu-diff-js (⭐19)](https://github.com/bokuweb/wu-diff-js) - A diff library to compute differences between two slices using wu(the O(NP)) algorithm.

### Validation

*   [is-kit (⭐196)](https://github.com/necoz-oss/is-kit) - Build small, composable type guards with natural TypeScript narrowing and zero dependencies.
*   [zod (⭐44k)](https://github.com/colinhacks/zod) - TypeScript-first schema validation with static type inference.

### Web framework

*   [alosaur (⭐817)](https://github.com/alosaur/alosaur) - Alosaur - Deno web framework with many ES Decorators.
*   [danet (⭐532)](https://github.com/Savory/Danet) - A Savory web framework for Deno heavily inspired by [Nest.js](https://nestjs.com).
*   [drash (⭐1.1k)](https://github.com/drashland/drash) - A REST microframework for Deno's HTTP server with zero dependencies.
*   [faster (⭐57)](https://github.com/hviana/faster) - A fast and optimized middleware server with a set of useful middlwares.
*   [faster\_react (⭐100)](https://github.com/hviana/faster_react) - Full Stack web framework with React + Faster. Fully compatible with Deno Deploy.
*   [hono (⭐33k)](https://github.com/honojs/hono) - Ultrafast web framework for Cloudflare Workers, Deno, and Bun. Fast, but not only fast.
*   [orpc (⭐5.8k)](https://github.com/middleapi/orpc) - End-to-end typesafe APIs with RPC and OpenAPI support, without code generation.

### Web utils

*   [forwarded (⭐8)](https://github.com/deno-libs/forwarded) - Deno port of `forwarded` library.
*   [gql (⭐205)](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware.
*   [graphql-tag (⭐8)](https://github.com/deno-libs/graphql_tag) - GraphQL schema AST from template literal.
*   [linkpeek (⭐18)](https://github.com/thegruber/linkpeek) - Extract Open Graph, Twitter Card and JSON-LD link-preview metadata from a URL.
*   [rpc (⭐23)](https://github.com/deno-libs/rpc) - JSONRPC server implementation for Deno.

### Webview

*   [webview (⭐1.6k)](https://github.com/webview/webview_deno) - Deno bindings for webview, a tiny library for creating web-based desktop GUIs.

## Registries

*   [deno.land/x/](https://deno.land/x/) - The official 3rd party module registry.

## Showcases

*   [Chobble Tickets (⭐37)](https://github.com/chobbledotcom/tickets) - Open source ticket sales system with encrypted attendee data and Stripe, Square, or SumUp payments.
*   [Deno Rest (⭐163)](https://github.com/Prolifode/deno_rest) - A Boilerplate for deno RESTful apis.
*   [GitHub Profile Trophy (⭐6.7k)](https://github.com/ryo-ma/github-profile-trophy) - 🏆 Add dynamically generated GitHub Trophy on your readme
*   [globnotes (⭐6)](https://github.com/alexindigo/globnotes) - Self-hosted Markdown note-taking app for Obsidian vaults and nested folders, with full-text search and sandboxed plugins.
*   [Medusa Edge API Gateway (⭐1)](https://github.com/glastor-core/medusa) - Resilient Edge API Gateway and caching proxy on Deno Deploy with circuit breaker, single-flight deduplication, and Deno KV.
*   [ShopSavvy Deno Deploy (⭐0)](https://github.com/shopsavvy/deno-deploy-shopsavvy) - Deno Deploy router with Hono for product search, real-time pricing, and price history.
*   [The Official Showcase](https://deno.com/showcase) - The official showcase of Deno.

## Tools

*   [bare-devcontainer/templates (⭐3)](https://github.com/bare-devcontainer/templates/tree/main/src/deno) - Security-focused Deno dev container for JS/TS with hardened defaults and cached modules. The base image is available at [bare-devcontainer/images (⭐3)](https://github.com/bare-devcontainer/images/tree/main/src/deno).
*   [clone (⭐4)](https://github.com/ekaragodin/clone) - A simple utility for the convenient clone.
*   [CompatLab (⭐4)](https://github.com/siddiksawani/CompatLab) - Check npm package loading across pinned Deno, Node.js and Bun versions with shareable reports.
*   [copilotz (⭐6)](https://github.com/copilotzhq/copilotz) - TypeScript runtime for apps used by people, the app's own agents and AI assistants over MCP, with one set of Actions, access rules and audit record for every caller.
*   [denoify (⭐949)](https://github.com/garronej/denoify) - For NPM module authors that would like to support Deno but do not want to write and maintain a port.
*   [denoliver (⭐104)](https://github.com/joakimunge/denoliver) - A simple, dependency free file server with live reload.
*   [denomander (⭐151)](https://github.com/siokas/denomander) - Deno command-line interfaces inspired from commander.js.
*   [denopkg (⭐238)](https://github.com/egoist-labs/denopkg.com) - An easier way to use code from GitHub in your Deno project.
*   [deno\_docker (⭐1k)](https://github.com/denoland/deno_docker) - Latest dockerfiles and images for Deno - alpine, centos, debian, ubuntu.
*   [dnt (⭐1.3k)](https://github.com/denoland/dnt) - Deno to npm package build tool.
*   dvm
    *   [asdf-community/asdf-deno (⭐132)](https://github.com/asdf-community/asdf-deno) - Deno plugin for [asdf](https://asdf-vm.com/)
    *   [justjavac/dvm (⭐714)](https://github.com/justjavac/dvm) - Deno Version Manager: manage multiple active Deno versions.
    *   [ghosind/dvm (⭐52)](https://github.com/ghosind/dvm) - A lightweight Deno Version Manager for Linux/MacOS.
*   [make-deno-edition (⭐42)](https://github.com/bevry/make-deno-edition) - Automatically makes package.json projects (such as npm packages and node.js modules) compatible with Deno.
*   [nemesis (⭐1)](https://github.com/glastor-core/nemesis) - Automated DevSecOps auditing, repository hygiene, auto-fix, and compliance CLI built with Deno 2.
*   [pup (⭐197)](https://github.com/Hexagon/pup) - Advanced process manager for Deno. With autorestart, fs watch, cron start, process telemetry, ipc, clustering, load balancer and more.
*   [studio-pack-generator (⭐128)](https://github.com/jersou/studio-pack-generator) - Convert a folder or a RSS URL to Studio pack for Lunii device
*   [vscode-deno (⭐1.5k)](https://github.com/denoland/vscode_deno) - VS Code extension that provides Deno support using the `TypeScript Deno language service plugin`.

## Integrations

*   [Netlify Edge Functions](https://docs.netlify.com/build/edge-functions/overview/) - Edge Functions connect the Netlify platform and workflow.
*   [Slack Custom Functions](https://docs.slack.dev/tools/deno-slack-sdk/guides/creating-custom-functions/) - Build custom Run On Slack functions using Deno.
*   [Smallweb](https://www.smallweb.run/) - A personal cloud contained in a single directory. You can customize the server behavior using Deno.
*   [Supabase Edge Functions](https://supabase.com/docs/guides/functions) - Edge Functions are server-side TypeScript functions, distributed globally at the edge.
*   [Astro](https://docs.astro.build/en/guides/deploy/deno/) - Deploy a server-side rendered Astro site to Deno Deploy.

## Blogs/Newsletters

*   [Deno Blog](https://deno.com/blog) - The official blog of the Deno Company.
*   [Deno News](https://deno.news) - A newsletter of Deno articles, news and cool projects.

## Articles

*   [Develop with Deno and Visual Studio Code](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
*   [First thoughts on Deno, the JavaScript/TypeScript run-time](https://43081j.com/2019/01/first-look-at-deno)
*   [Getting started with Deno](https://dev.to/wuz/getting-started-with-deno-e1m)
*   [What's Deno, and how is it different from Node.js?](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
*   [Write a small API using Deno](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
*   [Deno on Cloud Run](https://medium.com/google-cloud/deno-on-cloud-run-89ae64d1664d)
*   [Learn Deno: Chat app](https://aralroca.com/blog/learn-deno-chat-app)
*   [From Node to Deno](https://dev.to/aralroca/from-node-to-deno-5gpn)
*   [Create a simple Note-taking app with Deno](https://dev.to/jeferson_sb/create-a-simple-note-taking-app-with-deno-3k7g)
*   [Building API's using Deno, Oak and MYSQL](https://codeforgeek.com/building-api-server-using-deno-and-mysql/)
*   [Create your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)
*   [Continuous Integration with Deno](https://semaphoreci.com/blog/continuous-integration-with-deno)
*   [The Hidden Superpower of Deno: xeval](https://stefanbuck.com/blog/hidden-superpower-deno-xeval)
*   [Getting Started with Deno](https://sabe.io/tutorials/getting-started-with-deno)
*   [How to deploy a Deno app using Docker](https://sabe.io/tutorials/how-to-deploy-deno-app-docker)

## Presentations

*   [10 Things I Regret About Node.js - Ryan Dahl - JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
    *   [Slides](https://tinyclouds.org/jsconf2018.pdf)
*   [JSDC 2018#A01 - Deno, A New Server-Side Runtime By Ryan Dahl](https://www.youtube.com/watch?v=FlTG0UXRAkE)
*   [Ryan Dahl. Deno, a new way to JavaScript. JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
    *   [Slides](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
*   [Rafał Pocztarski — From Node.js to Deno - JavaScript/TypeScript runtime built with V8 and Rust \[EN\]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
*   [Ryan Dahl: A secure runtime for JavaScript and TypeScript | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
    *   [Slides](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
*   [Ryan Dahl: Deno, a new way to JavaScript - HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
    *   [Slides](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
*   [Rafał Pocztarski - What is Deno? A new runtime for modern JavaScript and TypeScript backends for 2020s - Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
*   [Michał Sabiniarz - How to contribute to Deno? - Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
*   [Bartek Iwańczuk - Deno internals, how modern runtime is built - Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
    *   [Slides](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
*   [Ryan Dahl & Kitson Kelly: Deno is a New Way to JavaScript - TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)
*   [Bert Belder - Deno - dotJS 2019](https://www.youtube.com/watch?v=puXyo1jGQys)
*   [Kitson P. Kelly - Deno, and The Future of JavaScript Runtimes - CityJS Conf 2020](https://www.youtube.com/watch?v=2eRyZpX4qvI)
*   [Matías Insaurralde - Deno: an experimental approach on V8 interoperability \[EN subtitles\] - NodeConf Argentina 2019](https://www.youtube.com/watch?v=N0BRE-0n2cU)
    *   [Slides](https://speakerdeck.com/matiasinsaurralde/deno-an-experimental-approach-on-v8-interoperability)

## Resources

### Books

*   [Modern Web Development with Deno](https://bpbonline.com/products/modern-web-development-with-deno)

## Resources in Other Languages

### Chinese

*   [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
*   [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
*   [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
*   [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
*   [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
*   [Node之父 - Deno，一个新的JS运行时](https://www.bilibili.com/video/av52038617)

### Hebrew

*   [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

### Indonesian

*   [Berkenalan dengan Deno](https://medium.com/@redhajuanda/berkenalan-dengan-dengan-deno-c48cdf3aa31e)
*   [Perkenalan Deno dan Instalasi](https://youtu.be/V_kpUTJSd9c)
*   [Deno Land Indonesia Telegram group](https://t.me/deno_id)

### Italian

*   [Deno - L'anagramma di Node](https://www.slideshare.net/FrancescoSciuti/deno-lanagramma-di-node)

### Japanese

*   [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
*   [mizchi/deno\_code\_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
*   [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
*   [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

### Russian

*   [Telegram channel](https://t.me/denoland_ru)
*   [Telegram chat](https://t.me/denoland)

### Spanish

*   [Hola Deno! . 🦕](https://medium.com/javascript-espa%C3%B1ol/hola-deno-f31f9f6f2c84)
*   [Así puedes crear tu primera API REST con Deno](https://medium.com/@mpampols/as%C3%AD-puedes-crear-tu-primera-api-rest-con-deno-a9094ee5c0b2)
*   [Primeros pasos con Deno 🦕 El sucesor de NodeJS desarrollado con Rust y TypeScript](https://medium.com/@manurua/primeros-pasos-con-deno-el-nuevo-nodejs-desarrollado-con-rust-y-typescript-b9ac14f7d0c7)
*   [Primer vistazo con deno](https://dev.to/buttercubz/first-look-with-deno-spanish-30dh)

### Darija

*   [A first look at Deno | BlaBlaConf 2021 🇲🇦](https://www.youtube.com/watch?v=Y_etUvzAa4s)

### Kurdish (Central)

*   [A short introduction to Deno](https://devs.krd/about-deno)

