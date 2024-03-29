# Awesome Cloudflare Overview

⛅️ Curated list of awesome Cloudflare worker recipes, open-source projects, guides, blogs and other resources.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/irazasyed/awesome-cloudflare/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 irazasyed/awesome-cloudflare](https://github.com/irazasyed/awesome-cloudflare) · ⭐ 404 · 🏷️ Platforms

[ [Daily](/content/irazasyed/awesome-cloudflare/README.md) / [Weekly](/content/irazasyed/awesome-cloudflare/week/README.md) / Overview ]

---

# Awesome Cloudflare [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) [<img src="https://github.com/irazasyed/awesome-cloudflare/raw/master/media/cf-logo.svg" width="250" align="right" alt="Cloudflare">](https://www.cloudflare.com)

> Curated list of awesome [Cloudflare](https://www.cloudflare.com) worker recipes, open-source projects, guides, blogs and other resources.

Cloudflare provides content delivery network (CDN) services, DDoS mitigation, Internet security and distributed domain name server (DNS) services, sitting between the visitor and the Cloudflare user's hosting provider, acting as a reverse proxy for websites.

## Contents

*   [Community](#community)
*   [Blog](#blog)
*   [DNS](#dns)
*   [Developers](#developers)
*   [Apps](#apps)
    *   [Open Source](#open-source)
*   [Workers](#workers)
    *   [Reference](#reference)
    *   [Tools](#tools)
    *   [Recipes](#recipes)
*   [Other](#other)

## Community

*   [Forum](https://community.cloudflare.com)
*   [Reddit](https://www.reddit.com/r/CloudFlare)
*   [`@Cloudflare` on Twitter](https://twitter.com/cloudflare)
*   [Facebook](https://www.facebook.com/Cloudflare)
*   [YouTube](https://www.youtube.com/cloudflare-)
*   [GitHub](https://github.com/cloudflare)
*   [GitHub Topic](https://github.com/topics/cloudflare)
*   [Stack Exchange](https://stackexchange.com/search?q=cloudflare)
*   [Stack Overflow](https://stackoverflow.com/questions/tagged/cloudflare)
*   [Server Fault](https://serverfault.com/questions/tagged/cloudflare)

## Blog

*   [Official Blog](https://blog.cloudflare.com)

## DNS

*   [DNS Zone Files (⭐46)](https://github.com/irazasyed/dns-zone-files) - Ready to import common config zone files for easy configuration of various services.
*   [Lexicon (⭐1.4k)](https://github.com/AnalogJ/lexicon) - CLI tool to manipulate DNS records on various DNS providers in a standardized way.
*   [Th3inspector (⭐1.8k)](https://github.com/Moham3dRiahi/Th3inspector) - All in one CLI tool for information gathering.
*   [Partner Panel (⭐1.3k)](https://github.com/ZE3kr/Cloudflare-CNAME-Setup) - Tool for hosting partners to provide a DNS management panel for customers.
*   [CFPMP (⭐243)](https://github.com/Netrvin/CFPMP) - Partner management panel.
*   [Flares (⭐174)](https://github.com/lfaoro/flares) - DNS backup tool.
*   [Block Bad Bot Ruleset (⭐179)](https://github.com/SukkaW/cloudflare-block-bad-bot-ruleset) - Collection of rulesets to block malicious crawlers with firewall rules.
*   [Docker DDNS (⭐954)](https://github.com/oznu/docker-cloudflare-ddns) - Docker image to use the free DNS Service as a dynamic DNS provider.
*   [DDNS script for Synology (⭐450)](https://github.com/joshuaavalon/SynologyCloudflareDDNS) - DDNS script for Synology NAS.
*   [Dynamic DNS Bash (⭐233)](https://github.com/yulewang/cloudflare-api-v4-ddns) - Dynamic DNS updater in bash script.
*   [Dynamic DNS PHP (⭐152)](https://github.com/lyoshenka/cloudflare-ddns) - Dynamic DNS updater in PHP.
*   [Dynamic DNS Python (⭐153)](https://github.com/adrienbrignon/cloudflare-ddns) - Dynamic DNS updater in python.
*   [Multi-Provider DDNS Script (⭐49)](https://github.com/phuslu/ddns) - Multiple providers ddns script without dependencies.
*   [Argo Tunnel Client (⭐5.8k)](https://github.com/cloudflare/cloudflared) - CLI client for Argo tunnel, a tunneling daemon that proxies any local webserver through the Cloudflare network.
*   [Upper (⭐99)](https://github.com/ostark/upper) - Speeds up craft dramatically using a cache proxy in front of your webserver.
*   [Cloud Buster (⭐143)](https://github.com/SageHack/cloud-buster) - A comprehensive pentest tool that checks sites for origin IP leaks.
*   [CLI Tool (⭐184)](https://github.com/danielpigott/cloudflare-cli) - CLI tool for interacting with Cloudflare.
*   [Detector (⭐18)](https://github.com/k4m4/cloudflare-detect) - Detect whether a site is running behind Cloudflare.
*   [Scrape (⭐3.1k)](https://github.com/Anorov/cloudflare-scrape) - Python module to bypass anti-bot page.
*   [CloudFlair (⭐1.9k)](https://github.com/christophetd/CloudFlair) - Tool to find origin servers of websites protected by CloudFlare who are publicly exposed.

## Developers

*   [Developers Hub](https://developers.cloudflare.com) - Developer docs including API reference, articles, and sample code for all products.
*   [Open Source](https://cloudflare.github.io) - Official open-source projects.
*   [API Docs](https://api.cloudflare.com) - API documentation.
*   [Integration Resources](https://www.cloudflare.com/integrations) - Plugins for content management systems, control panels, cloud providers, ecommerce platforms and more.
*   [Technical Resources](https://www.cloudflare.com/technical-resources) - Technical tools and resources.
*   [The Serverlist Newsletter](https://blog.cloudflare.com/serverlist) - The serverlist is a Cloudflare-curated newsletter about all things serverless.

## Apps

> [Cloudflare Apps](https://www.cloudflare.com/apps/developers) lets you ship your tool or service to millions of sites. Any Cloudflare customer can preview & install your code on their site in seconds.

*   [Apps Directory](https://www.cloudflare.com/apps)
*   [Documentation](https://www.cloudflare.com/apps/developer/docs/getting-started)
*   [Developer Fund](https://www.cloudflare.com/fund)
*   [App Ideas (⭐41)](https://github.com/cloudflare-apps/ideas)

### Open Source

*   [Official OSS Apps](https://github.com/cloudflare-apps) - Collection of official apps.
*   [Logflare (⭐38)](https://github.com/Logflare/cloudflare-app) - Log management & event analytics.
*   [OpWork.dev (⭐9)](https://github.com/hisorange/opwork) - Self hosted CloudFlare workers management platform.

## Workers

> [Cloudflare Workers](https://www.cloudflare.com/products/cloudflare-workers) provides a serverless execution environment that allows you to create entirely new applications or augment existing ones without configuring or maintaining infrastructure.

### Reference

*   [Documentation](https://workers.cloudflare.com/docs)
*   [Tutorials](https://workers.cloudflare.com/docs/tutorials)
*   [Runtime](https://workers.cloudflare.com/docs/reference/runtime)
*   [Workers KV](https://workers.cloudflare.com/docs/reference/storage)

### Tools

*   [Wrangler (⭐3.2k)](https://github.com/cloudflare/wrangler) - `wrangler` is a CLI tool designed for folks who are interested in using Cloudflare workers.
*   [Playground](https://www.cloudflareworkers.com) - Simple, instant way to preview and test code directly in the browser against any site.
*   [Serverless Plugin](https://workers.cloudflare.com/docs/reference/tooling/serverless) - Plugin for [serverless framework (⭐45k)](https://github.com/serverless/serverless) to develop and deploy serverless applications using Workers.
*   [Worker App Kit (⭐82)](https://github.com/postlight/cloudflare-worker-app-kit) - Handy set of tools for creating, developing, testing, and deploying worker app.
*   [GitHub Action (⭐19)](https://github.com/cpilsworth/cloudflare-worker-action) - Deploy a worker on push to the master branch.
*   [Workers KV Viewer (⭐38)](https://github.com/jroyal/cloudflare-workers-kv-viewer) - CLI based interactive viewer for workers KV storage.
*   [Redirect Management](https://forwarding.app) - Generate redirect worker.

### Recipes

*   [Examples Collection (⭐932)](https://github.com/cloudflare/worker-examples) - Collection of recipes.
*   [Hello World JS Boilerplate (⭐151)](https://github.com/cloudflare/worker-template) - Template for kick starting a worker project in JS.
*   [Hello World Rust Boilerplate (⭐350)](https://github.com/cloudflare/rustwasm-worker-template) - Template for kick starting a worker project using wasm-pack.
*   [Router (⭐216)](https://github.com/cloudflare/worker-template-router) - Router that can be used with REST APIs or apps for basic routing logic.
*   [Static (⭐13)](https://github.com/cloudflare/worker-template-static) - Generate a static HTML or JSON page from raw strings in your workers script.
*   [Fetch (⭐17)](https://github.com/cloudflare/worker-template-fetch) - Examples of making fetch requests and generating JSON post requests.
*   [Incoming Request (⭐0)](https://github.com/ashleygwilliams/worker-template-requests) - Examples of reading in a POST request body of type JSON and form-data.
*   [Redirect (⭐9)](https://github.com/cloudflare/worker-template-redirect) - Examples of sending single and bulk redirects from a Worker script.
*   [Img-Color (⭐36)](https://github.com/xtuc/img-color-worker) - Retrieve the dominant color of a png or jpeg image.
*   [Binast (⭐7)](https://github.com/xtuc/binast-cf-worker-template) - Serve binast via a worker.
*   [Pwnage Protection (⭐147)](https://github.com/detroitenglish/pw-pwnage-cfworker) - Secure password scoring and user pwnage protection api - [Usage](https://community.cloudflare.com/t/estimate-strength-of-users-new-password-input-with-zxcvbn-and-query-haveibeenpwned-for-matches-against-known-hacked-accounts/26378).
*   [Cache Purger Proxy](https://gist.github.com/vdbelt/20f116236d2ebffa92f131e679c0551a) - Proxies purge cache requests - [Usage](https://community.cloudflare.com/t/worker-recipe-cache-purge-proxy/29978).
*   [URL Router (⭐88)](https://github.com/berstend/service-worker-router) - Fast url router - [Usage](https://community.cloudflare.com/t/open-source-fast-url-router-for-workers-js-typescript/33406).
*   [Edge Proxy (⭐72)](https://github.com/DigitalOptimizationGroup/cloudflare-edge-proxy) - Enable A/B testing, canary releasing, gatekeeping, and SEO A/B/N testing.
*   [Blue / Green Deployments (⭐24)](https://github.com/DigitalOptimizationGroup/blue-green-cloudflare-workers) - Working example of blue / green deployments with canary releasing.
*   [Preact PWA (⭐61)](https://github.com/DigitalOptimizationGroup/cloudflare-worker-preact-pwa) - Preact progressive web app.
*   [CURL Interceptor (⭐44)](https://github.com/Gaafar/curl-worker) - Intercepts requests from `curl` command and returns something different.
*   [Worker with built-in Router (⭐40)](https://github.com/anderly/cloudflare-worker-routing) - Allows you to separate your worker logic into different functions and/or controllers.
*   [Connecting to Google Storage](https://community.cloudflare.com/t/connecting-to-google-storage/32350) - Pull files from Google's cloud storage.
*   [CSRF Protection](https://gist.github.com/simonerni/3501b8de6320ac37398d08d9d2d08561) - Protect any origin from CSRF by verifying origin/referer headers.
*   [URL Query Strings Parser](https://community.cloudflare.com/t/parse-url-query-strings-with-cloudflare-workers/90286) - Parse url query strings.
*   [Regrex Replacement and Injection](https://community.cloudflare.com/t/perform-regex-replacements-and-inject-css-javascript-with-cloudflare-workers/90279) - Perform regex replacements and inject CSS/JS.
*   [Webpack Boilerplate (⭐122)](https://github.com/detroitenglish/cloudflare-workers-webpack-boilerplate) - Boilerplate to build, bundle and deploy workers with webpack.
*   [Basic Auth (⭐102)](https://github.com/dommmel/cloudflare-workers-basic-auth) - Protection using basic auth.
*   [Send Logs to Logdna (⭐25)](https://github.com/boynet/cf-logdna-worker) - Simple recipe to send logs to logdna.
*   [IP lookup service (⭐33)](https://github.com/matthewgall/beta.ipinfo.in) - IP lookup service using workers.
*   [Airtable Proxy (⭐124)](https://github.com/portable-cto/airtable-proxy-worker) - Allows you to make secure requests to the Airtable API from your frontend.
*   [TypeScript Workers (⭐139)](https://github.com/udacity/cloudflare-typescript-workers) - Types and mocks for building a tested typescript worker.
*   [Proxies (⭐88)](https://github.com/GitbookIO/proxies-on-cloudflare) - Makes it easy to build workers, by providing high-level proxying primitives addressing common needs.
*   [Static Worker (⭐9)](https://github.com/manatarms/static-worker) - Provides functions that make it easy to host a static website.
*   [Bannero (⭐5)](https://github.com/nondanee/bannero) - Bannero image API for simpledesktops.
*   [Hasura (⭐18)](https://github.com/nathanwaters/hasura-cloudflare-worker) - Example using Facebook-based authorization and graphql proxy queries with hasura.
*   [IP Redirects](https://community.cloudflare.com/t/ip-redirects/18285) - Redirect users based on their ip address.
*   [Switch Image to WebP](https://github.com/vidaxl-com/cloudflare_webworkers/blob/master/examples/webp.js) - Reroute image to webp when supported.
*   [Geographic Routing and Load Balancer](https://community.cloudflare.com/t/geographic-routing-and-load-balancing-with-cloudflare-workers/21900) - Geographic routing and load balancing with workers.
*   [UTM Tag Stripper](https://community.cloudflare.com/t/strip-utm-query-string/47941) - Strip UTM tags in query string.
*   [Short URL Redirector](https://community.cloudflare.com/t/short-url-using-workers/39877) - Redirect short links.
*   [Repo Hunt (⭐40)](https://github.com/signalnerve/repo-hunt) - Find cool open-source projects daily.
*   [Performance Optimized Workers (⭐145)](https://github.com/pmeenan/cf-workers) - Collection of worker scripts, generally focused on performance optimizations.
*   [Google reCAPTCHA verification (⭐33)](https://github.com/HR/recaptcha-worker) - Handle the server-side verification of your reCAPTCHA form.
*   [Cloudflare Workers Starter Kit (⭐57)](https://github.com/kriasoft/cloudflare-starter-kit) -  - TypeScript template \w multiple CF Workers, `*.env` files, and local testing.

## Other

*   [Support](https://support.cloudflare.com)
*   [System Status](https://www.cloudflarestatus.com)
*   [Network Map](https://www.cloudflare.com/network)

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/irazasyed/awesome-cloudflare/blob/master/readme.md/contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Irfaq Syed](https://github.com/irazasyed) has waived all copyright and
related or neighboring rights to this work.

> Cloudflare is a registered trademark of Cloudflare, Inc.

