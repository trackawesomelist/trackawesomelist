# Awesome Choo Overview

🌅 Awesome things related with choo framework

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/choojs/awesome-choo/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 choojs/awesome-choo](https://github.com/choojs/awesome-choo) · ⭐ 191 · 🏷️ Front-End Development

[ [Daily](/content/choojs/awesome-choo/README.md) / [Weekly](/content/choojs/awesome-choo/week/README.md) / Overview ]

---

# Awesome choo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <div align="right">:steam\_locomotive::train::train::train::train::train:</div>

> [choo](https://choo.io/) is a `4kb` framework for creating
> sturdy frontend applications

## Contents

*   [Official resources](#official-resources)
*   [Dependencies](#dependencies)
*   [Demos](#demos)
*   [Community](#community)
*   [Plugins and addons](#plugins-and-addons)
*   [Elements](#elements)
*   [CLI Templates](#cli-templates)
*   [Resources](#resources)
*   [Projects using choo](#projects-using-choo)

### Official resources

*   [Docs (⭐6.7k)](https://github.com/yoshuawuyts/choo/blob/master/README.md)
*   [Handbook (⭐266)](https://github.com/yoshuawuyts/choo-handbook)
*   [Repo (⭐6.7k)](https://github.com/yoshuawuyts/choo)
*   [Website](https://choo.io/)
*   [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Dependencies

`choo` is a modular framework. These are the dependencies it glues together
under the hood:

*   [bel (⭐672)](https://github.com/shama/bel) - Create composable DOM elements using
    template strings.
*   [hyperx (⭐993)](https://github.com/substack/hyperx) - Convert template strings to
    library backends.
*   [nanomorph (⭐684)](https://github.com/choojs/nanomorph) - Hyper fast diffing algorithm for real DOM nodes.
*   [nanoraf](https://github.com/yoshuawuyts/nanoraf) - Only call RAF when needed.
*   [nanorouter (⭐117)](https://github.com/choojs/nanorouter) - Smol frontend router.
*   [nanobus (⭐215)](https://github.com/choojs/nanobus) - Tiny message bus.
*   [nanolocation (⭐10)](https://github.com/choojs/nanolocation) - Small window\.location library.
*   [nanohref (⭐40)](https://github.com/choojs/nanohref) - Tiny href click handler library.
*   [nanoquery (⭐48)](https://github.com/choojs/nanoquery) - Tiny querystring module.
*   [nanotiming (⭐34)](https://github.com/choojs/nanotiming) - Small timing library.

### Demos

*   [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo (⭐6.7k)](https://github.com/yoshuawuyts/choo/tree/master/examples/title))
*   [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
*   [Mailbox routing (⭐6.7k)](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox)
*   [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo (⭐39)](https://github.com/shuhei/todomvc-choo))
*   [choo-firebase](https://choo-firebase-2ec21.firebaseapp.com) - ([repo (⭐19)](https://github.com/mw222rs/choo-firebase))
*   [Grow](https://grow.static.land) - ([repo (⭐13)](https://github.com/sethvincent/grow))
*   [Chatbot](http://chootbot.herokuapp.com) - ([repo (⭐2)](https://github.com/plaey/chatbot))
*   [chat-random](https://github.com/akiva/chat-random)
*   [choo-leaflet-demo (⭐16)](https://github.com/timwis/choo-leaflet-demo)
*   [choo-scriber](https://zhouhansen.github.io/choo-scriber) - ([repo (⭐6)](https://github.com/ZhouHansen/choo-scriber))

### Community

*   [Freenode](https://webchat.freenode.net/?channels=choo)

### Plugins and addons

*   [choo-location-electron (⭐12)](https://github.com/bcomnes/choo-location-electron) - Fix `choo`'s router in electron.
*   [choo-log (⭐46)](https://github.com/yoshuawuyts/choo-log) - Development logger for choo.
*   [choo-test (⭐23)](https://github.com/mantoni/choo-test) - Easy choo app unit testing.
*   [choo-persist (⭐44)](https://github.com/yoshuawuyts/choo-persist/) - Synchronize choo state with LocalStorage.
*   [choo-promise (⭐4)](https://github.com/rahatarmanahmed/choo-promise) - Use promises in effects and subscriptions.
*   [choo-pull (⭐15)](https://github.com/yoshuawuyts/choo-pull) - Wrap handlers to use pull-stream in a choo plugin.
*   [choo-redirect (⭐19)](https://github.com/yoshuawuyts/choo-redirect) - Redirect a view to another view.
*   [choo-model (⭐14)](https://github.com/yoshuawuyts/choo-model) - Experimental state management lib for choo.
*   [choo-resume (⭐15)](https://github.com/bengourley/choo-resume) - choo-resume + hot-rld = hot app reload in choo.
*   [choo-detached (⭐19)](https://github.com/graforlock/choo-detached) - Use `choo` as a mountable, simple stand-alone component (no routing).
*   [choo-service-worker (⭐25)](https://github.com/choojs/choo-service-worker) - Service worker loader for `choo`.
*   [choo-websocket (⭐28)](https://github.com/YerkoPalma/choo-websocket) - Small wraper around WebSocket browser API, for `choo` apps.
*   [choo-store (⭐39)](https://github.com/ungoldman/choo-store) - Lightweight state structure for choo apps.

### Elements

*   [dom-notifications (⭐108)](https://github.com/finnp/dom-notifications) - Atom-inspired notifications component.
*   [choodown (⭐14)](https://github.com/trainyard/choodown) - A simple markdown component for choo.
*   [choo-md-editor (⭐5)](https://github.com/dbtek/choo-md-editor) - Lightweight markdown editor that can be used inside Choo app or as a standalone library.
*   [choo-chartist (⭐8)](https://github.com/rexmortus/choo-chartist) - A little component for using [Chartist](https://gionkunz.github.io/chartist-js/) with the choo framework.

### CLI Templates

Templates for [choo-cli (⭐65)](https://github.com/trainyard/choo-cli)

*   [trainyard/template-basic (⭐2)](https://github.com/trainyard/template-basic)
*   [haroenv/template-webpack (⭐7)](https://github.com/haroenv/template-webpack)
*   [simonwjackson/atomic-choo](https://github.com/simonwjackson/atomic-choo) - An opinionated project seed to get started developing with electron, webpack and choo.

Other CLI templates

*   [graforlock/choo-bandwagon (⭐13)](https://github.com/graforlock/choo-bandwagon)

### Resources

> :movie\_camera: : videos
> :computer: : tutorials
> :book: : articles

*   :computer: [Your first choo app](https://yoshuawuyts.gitbooks.io/choo/content/02_your_first_app.html)
*   :movie\_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
*   :book: [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
*   :book: [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
*   :book: [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Projects using choo

*   [boxcar (⭐10)](https://github.com/toddself/boxcar) - A choo-based grid/spreadsheet editor.
*   [choo-sortable (⭐2)](https://github.com/willkessler/choo-sortable) - Building sortable code with choo.
*   [hacker-choo (⭐10)](https://github.com/mw222rs/hacker-choo) - Hacker Typer clone written in choo.
*   [footprint-rechoo (⭐4)](https://github.com/npeihl/footprint-rechoo) - A choo rewrite of [footprint-review (⭐6)](http://github.com/sjcgis/footprint-review).
*   [minidocs (⭐136)](https://github.com/freeman-lab/minidocs) – A documentation site generator built with choo.
*   [dataface (⭐43)](https://github.com/timwis/dataface) - Desktop application to manage databases.
*   [BlankUp (⭐38)](https://github.com/HoverBaum/BlankUp-Electron) - Multiplatform markdown editor.
*   [hackernews-choo (⭐30)](https://github.com/kvnneff/hackernews-choo) - A Hacker News reader built with choo.
*   [tic-tac-choo (⭐6)](https://github.com/YerkoPalma/tic-tac-toe) - Progressive tic tac toe game, made with choo.
*   [enviar (⭐34)](https://github.com/timwis/enviar) - Chat interface for SMS / text messages.
*   [kaktus (⭐0)](https://github.com/kaktus/kaktus) - A new minimalistic web browser, built on `choo` and IndexedDB.
*   [civicdr.org (⭐3)](https://github.com/CiviCDR/civicdr.org) - Website for [CiviCDR](https://civicdr.org/).
*   [nekocafe (⭐16)](https://github.com/notenoughneon/nekocafe) - Web chat room :cat: :speech\_balloon:.
*   [Robotopia (⭐502)](https://github.com/robotopia-x/robotopia) - Introducing kids to coding with tiny virtual robots!
*   [busca (⭐10)](https://github.com/afk-mcz/busca) - A small web-extension to search the current tab on reddit.
*   [choo-ban (⭐5)](https://github.com/luizbaldi/choo-ban) - Simple kanban to manage board tasks, built with `choo`.
*   [boowa (⭐43)](https://github.com/boowajs/boowa) - A fun blog generator, built with `choo`.
*   [hyperamp (⭐294)](https://github.com/hypermodules/hyperamp) - Humble music player.

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yerko Palma](https://github.com/YerkoPalma) has waived all copyright and related or neighboring rights to this work.

