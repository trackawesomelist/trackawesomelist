# Awesome Yew Overview

😎 A curated list of awesome things related to Yew / WebAssembly.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/jetli/awesome-yew/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 jetli/awesome-yew](https://github.com/jetli/awesome-yew) · ⭐ 1.5K · 🏷️ Front-End Development

[ [Daily](/content/jetli/awesome-yew/README.md) / [Weekly](/content/jetli/awesome-yew/week/README.md) / Overview ]

---

# Awesome Yew [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://github.com/jetli/awesome-yew/raw/master/logo.svg" align="right" width="100" title="Awesome Yew">](https://github.com/yewstack/yew)

> A curated list of awesome things related to Yew.

[Yew (⭐31k)](https://github.com/yewstack/yew) is a modern Rust framework inspired by Elm and React for creating multi-threaded frontend apps with WebAssembly.

Contributions welcome! Read the [contribution guidelines](https://github.com/jetli/awesome-yew/blob/master/README.md/CONTRIBUTING.md) first.

## Contents

*   [Official](#official)
*   [Projects](#projects)
*   [Templates](#templates)
*   [Crates](#crates)
    *   [Component Libraries](#component-libraries)
    *   [Components](#components)
    *   [Hooks](#hooks)
    *   [Utils](#utils)
    *   [Wasm](#wasm)
*   [Tooling](#tooling)
*   [Articles](#articles)
*   [Books](#books)
*   [Alternatives](#alternatives)
*   [Related lists](#related-lists)

## Official

*   [Yew (⭐31k)](https://github.com/yewstack/yew) - Rust / WebAssembly framework for building client web apps.
*   [Live demo](https://yew-todomvc.netlify.com) - A todomvc demo.
*   [Examples (⭐31k)](https://github.com/yewstack/yew/tree/master/examples) - Smaller examples included in official repo.
*   [API Docs](https://docs.rs/yew) - Docs on docs.rs.
*   [Website](https://yew.rs/) - Official website.
*   [Chatroom](https://discord.gg/VQck8X4) - It is pretty active and is a great place to ask questions.
*   [Reddit](https://www.reddit.com/r/yew_web/) - Dedicated Sub Reddit.
*   [Financial Contribute](https://opencollective.com/yew) - Become a financial contributor and help us sustain our community.
*   [Playground](https://play.yew.rs) - Online playground for Yew.

## Projects

*   [Realworld example (⭐879)](https://github.com/jetli/rust-yew-realworld-example-app) - Exemplary real world app built with Rust + Yew + WebAssembly. It utilizes Yew's latest `function components` and `hooks`. It also supports desktop application powered by [Tauri (⭐90k)](https://github.com/tauri-apps/tauri).
*   [webapp.rs (⭐2.2k)](https://github.com/saschagrunert/webapp.rs) - A web application completely written in Rust, frontend is built with Yew.
*   [Rust-Full-Stack (⭐1.6k)](https://github.com/steadylearner/Rust-Full-Stack) - Easily testable and working Rust codes with blog posts to explain them.
*   [Bucket Questions (⭐5)](https://github.com/hgzimmerman/BucketQuestions) - A webapp written entirely in Rust for a dumb party game.
*   [web-view todomvc desktop app (⭐111)](https://github.com/Extrawurst/rust-webview-todomvc-yew) - Demo how to use yew for a todomvc that compiles to WebAssembly and is bundled as a lightweight(\~2mb) desktop app by [web-view (⭐1.9k)](https://github.com/Boscop/web-view), as an alternative to Electron, [web-view (⭐1.9k)](https://github.com/Boscop/web-view) also has a [demo (⭐1.9k)](https://github.com/Boscop/web-view/tree/master/examples#todo-yew).
*   [yew-react-example (⭐66)](https://github.com/hobofan/yew-react-example) - This project shows how to create a web app using a React component inside a Yew component.
*   [Kirk (⭐43)](https://github.com/stkevintan/Kirk) - Just A Rust WebAssembly Blog.
*   [rust-async-wasm-demo (⭐49)](https://github.com/extraymond/rust-async-wasm-demo) - Toy project to learn Rust and async that can be deployed to the web.
*   [karaoke-rs (⭐165)](https://github.com/tarkah/karaoke-rs) - A simple, network enabled karaoke player in Rust.
*   [I Love Hue! (rs) (⭐25)](https://github.com/noc7c9/i-love-hue-rs) - A clone of the mobile game I Love Hue in Yew (Rust).
*   [yew-styles-page (⭐157)](https://github.com/spielrs/yew-styles-page) - This is an initial project of a framework style for yew.
*   [caniuse.rs (⭐178)](https://github.com/jplatte/caniuse.rs) - Rust feature search.
*   [Rust electron yew demo (⭐17)](https://github.com/Extrawurst/rust-electron-demo) - An example of building a Rust based web app (Yew) into a native app using electron.
*   [covplot (⭐21)](https://github.com/jbowens/covplot) - Live graphs of worldwide CoVID-19 data.
*   [Minesweeper (⭐37)](https://github.com/jgpaiva/minesweeper) - Minesweeper built with Rust, Yew and WebAssembly.
*   [Freecell (⭐6)](https://github.com/Stigjb/freecell) - A patience game written in Rust and Yew.
*   [Yew-WebRTC-Chat (⭐127)](https://github.com/codec-abc/Yew-WebRTC-Chat) - A simple WebRTC chat made with Yew.
*   [Yew Fullstack Boilerplate (⭐58)](https://github.com/lukidoescode/yew-fullstack-boilerplate) - Highly opinionated boilerplate for creating full stack applications with Rust.
*   [Chord Quiz (⭐16)](https://github.com/Stigjb/chord-quiz) - Practice recognizing chords in this Rust/Yew/WebAssembly app.
*   [RustMart (⭐272)](https://github.com/sheshbabu/rustmart-yew-example) - Single Page Application (SPA) written using Rust, Wasm and Yew.
*   [DevAndDev (⭐39)](https://github.com/alepez/devand) - A website where developers can find pair-programming partners. Written in Rust, Yew frontend.
*   [yew-octicons (⭐19)](https://github.com/io12/yew-octicons) - An easy interface for using Octicons in Yew projects.
*   [Pipe (⭐32)](https://github.com/pipe-fun/pipe) - This is a Rust / Wasm client web app which is a task control center.
*   [note-to-yew (⭐3)](https://github.com/oovm/note-to-yew) - Convert your markups into Yew macro online, which is also made by Yew.
*   [ASCII-Hangman (⭐7)](https://github.com/getreu/ascii-hangman) - Configurable Hangman game for children with ASCII-art rewarding.
*   [dotdotyew (⭐3)](https://github.com/shaunbennett/dotdotyew) - [Dot-voting](https://en.wikipedia.org/wiki/Dot-voting) using Yew, with Rust powering the backend API.
*   [wasm-2048 (⭐154)](https://github.com/dev-family/wasm-2048) - 2048 game implemented with Rust and Yew and compiled to Wasm.
*   [website-wasm (⭐58)](https://github.com/kamiyaa/website-wasm) - My personal website written in Rust via Yew/Wasm.
*   [KeyPress (⭐8)](https://github.com/rayylee/keypress) - A Rust WebAssembly Website example for practising english for chinese.
*   [yew-train-ticket (⭐4)](https://github.com/anthhub/yew-train-ticket) - A Rust WebAssembly [Webapp](http://118.190.37.169:8002) example basing Yew newest hooks and functional API, the code style is extremely like React Function Component.
*   [yew-d3-example (⭐24)](https://github.com/ivanschuetz/yew-d3-example) - Showing a d3 chart with Yew.
*   [Oxfeed (⭐11)](https://github.com/sanpii/oxfeed) - A feed reader written in Rust with a Yew frontend.
*   [Flow.er (⭐54)](https://github.com/LighghtEeloo/flow.er) - A notebook app integrated with todo lists utility. Developed with Rust, WebAssembly, Yew and Trunk.
*   [Fullstack-Rust (⭐97)](https://github.com/vascokk/fullstack-rust) - A Full Stack Rust application (Connect5 game) with Actix-web, Yew, Bulma CSS and Diesel.
*   [Sea\_battle (⭐1)](https://github.com/MAE664128/sea_battle) - A simple example of a sea battle game. Rust + Yew.
*   [tide-async-graphql-mongodb (⭐45)](https://github.com/zzy/tide-async-graphql-mongodb) - Clean boilerplate for graphql services, with wasm/yew frontend.
*   [surfer (⭐53)](https://github.com/zzy/surfer) - A blog built on yew + graphql, with [live demo site](https://niqin.com). Backend for graphql services, and frontend for web application.
*   [qubit](https://abhimanyu003.github.io/qubit) - A handy calculator, based on Rust and WebAssembly, [Live Demo](https://abhimanyu003.github.io/qubit/).
*   [Paudle (⭐42)](https://github.com/pmsanford/paudle) - A reimplementation of the excellent word game Wordle by Josh Wardle.
*   [Rust algorithms (⭐116)](https://github.com/Jondolf/rust-algorithms) - A website with interactive implementations of various algorithms.
*   [Marc Portfolio](https://gitlab.com/marcempunkt/maeurerdev) - A software developer portfolio, [Live Demo](https://maeurer.dev/).
*   [zzhack (⭐327)](https://github.com/zzhack-stack/zzhack) - A personal blog, based on Rust & Yew, [Live Demo](https://www.zzhack.fun/).
*   [Rquote (⭐3)](https://github.com/Altair-Bueno/rquote) - Rquote is a web application built using Rust and WebAssembly. It fetches Anime quotes from the Animechan API. [Live Demo](https://rquote.vercel.app/).
*   [yew-ssr-tide (⭐1)](https://github.com/zzy/yew-ssr-tide) - The example demonstrates Yew server-side rendering with tide & surf, it needs the **development version** of Yew.
*   [yew-ssr-actix-web (⭐16)](https://github.com/zzy/yew-ssr-actix-web) - The example demonstrates Yew server-side rendering with actix-web & reqwest, it needs the **development version** of Yew.
*   [PixelGuesser (⭐8)](https://github.com/tdooms/pixelguesser) - PixelGuesser is a real life party gam where players try to guess the contents of an image as quickly as possible.
*   [Crabtyper (⭐188)](https://github.com/brancobruyneel/crabtyper) - A speedtyping web app written in Rust.
*   [We-Come Monorepo (⭐1)](https://github.com/kabinetkmitb/wecome) - This is a monorepo for wecome KM ITB, [Live Demo](https://wecome-itb.com/).
*   [blog-rs (⭐58)](https://github.com/songday/blog-rs) - A blog system in which frontend and backend are ALL written in Rust. Backend powered by Warp and frontend built on Yew (WASM).
*   [mb2](https://devctm.com) - A poker server with a Yew client. Click the `Demo` button and then `Start` to see the client.
*   [Puzzle Cube (⭐9)](https://github.com/wainwrightmark/puzzle_cube) - Rubix Cube solver using Rust and Yew, [Live Demo](https://wainwrightmark.github.io/puzzle_cube/).
*   [CubeShuffle (⭐25)](https://github.com/philipborg/CubeShuffle) - Card game shuffling utility built with Rust, Yew, Bulma and Tauri.
*   [Rust Audio (⭐52)](https://github.com/austintheriot/audio) - Realtime audio processing / synthesis using Rust/WASM in the browser, [Live Demo](https://austintheriot.github.io/audio/).
*   [Kiomet (⭐100)](https://github.com/SoftbearStudios/kiomet) - An online real-time strategy game in which you expand your territory by capturing towers.
*   [Portfolio website (⭐12)](https://github.com/simbleau/website) - A portfolio SPA with accessibility built-in by Spencer Imbleau.
*   [tchatche.rs (⭐202)](https://github.com/nag763/tchatchers) - A Websocket chat based application built in Yew and Axum.
*   [viz.rs (⭐13)](https://github.com/viz-rs/viz-rs.github.io) - A website for viz web framework, [Live Demo](https://viz.rs/).
*   [theiskaa.com (⭐1)](https://github.com/theiskaa/theiskaa.com) - A real world implementation of Yew framework. [Live at theiskaa.com](https://theiskaa.com).
*   [live-ask.com (⭐101)](https://github.com/liveask/liveask) - Realtime Event/Meetup Q\&A Platform. [Live at live-ask.com](https://live-ask.com).
*   [Sumi (⭐10)](https://github.com/vgwidt/sumi) - Multi-user issue tracking and knowledge base app built with Yew & Actix.
*   [hurlurl (⭐65)](https://github.com/lucasmerlin/hurlurl) - A randomizing link shortener, [Live Demo](https://hurlurl.com/).
*   [Macige (⭐95)](https://github.com/tramlinehq/macige) - CI workflow generator for mobile app development, [Live Demo](https://macige.tramline.app).
*   [Spaceman (⭐370)](https://github.com/eliaperantoni/spaceman) - Spaceman is a cross-platform gRPC client designed to be pleasant to use and pretty to look at.
*   [Crypto-helper (⭐36)](https://github.com/TheBestTvarynka/crypto-helper) - Web app that can hash, encrypt, and sign the data on the client side. Also includes a JWT debugger. [Website](https://crypto.qkation.com).
*   [zoom-rs (⭐1.5k)](https://github.com/security-union/zoom-rs) - Zoom clone written in rust for research purposes.
*   [Ubiquity (⭐191)](https://github.com/opensourcecheemsburgers/ubiquity) - An open-source, cross-platform markdown editor; built with Yew, Tauri, Tailwind, and DaisyUI. [Web App](https://ubiquity.rs).
*   [demo\_web\_zip\_wasm (⭐6)](https://github.com/MAE664128/demo_web_zip_wasm) - A simple example program for creating ZIP archives running in the browser using WebAssembly, [Live Demo](https://mae664128.github.io/demo_web_zip_wasm/).
*   [RustedLessPass (⭐53)](https://github.com/RustedLessPass/RustedLessPass) - A stateless password manager. [Web App](https://rustedlesspass.github.io/).
*   [windows-terminal-theme-generator (⭐18)](https://github.com/LelouchFR/windows-terminal-theme-generator/) - Simplify your life to create a windows terminal theme. [Live Demo](https://windows-terminal-theme-generator.netlify.app/)
*   [SandCat (⭐53)](https://github.com/Xu-Mj/sandcat) - The software has primarily implemented the basic functionalities of an IM application, which includes a fundamental friend system, one-on-one chat, group chat, and one-on-one audio/video calls. It also supports i18n and currently offers a switch between Chinese and English.
*   [PinePods (⭐372)](https://github.com/madeofpendletonwool/PinePods) - PinePods is a Rust based podcast management system that manages podcasts with multi-user support and relies on a central database with clients to connect to it.
*   [0721 (⭐11)](https://github.com/langyo/0721) - The engine of image hosting written in Rust.
*   [Hikari (⭐21)](https://github.com/celestia-island/hikari) - The Frontend of Everything.
*   [simply-view-image-for-python-debugging (⭐63)](https://github.com/elazarcoh/simply-view-image-for-python-debugging?tab=readme-ov-file) - Visual studio code extension simply view the image of the image variables when debugging python.
*   [Mindsweeper (⭐74)](https://github.com/AlexBuz/mindsweeper) - A principled take on minesweeper, [Live Demo](https://alexbuz.github.io/mindsweeper/).
*   [scap-rs (⭐19)](https://github.com/emo-crab/scap-rs) - National Vulnerability Database (NVD) implemented by Rust, [Live Demo](https://scap.kali-team.cn/).
*   [Sentry Relay (⭐336)](https://github.com/getsentry/relay) - The Sentry Relay is a service that pushes some functionality from the Sentry SDKs as well as the Sentry server into a proxy process.
*   [Syre (⭐17)](https://github.com/syre-data/syre) - Scientific data management and insights.
*   [candle-wasm-examples (⭐17k)](https://github.com/huggingface/candle) - Candle is a minimalist ML framework for Rust with a focus on performance (including GPU support) and ease of use. Try our online demos: [whisper](https://huggingface.co/spaces/lmz/candle-whisper), [LLaMA2](https://huggingface.co/spaces/lmz/candle-llama2), [T5](https://huggingface.co/spaces/radames/Candle-T5-Generation-Wasm), [yolo](https://huggingface.co/spaces/lmz/candle-yolo), [Segment
    Anything](https://huggingface.co/spaces/radames/candle-segment-anything-wasm).
*   [chipbox (⭐105)](https://github.com/chipnertkj/chipbox) - chipbox is an open-source desktop DAW written in Rust.
*   [Taxy (⭐125)](https://github.com/picoHz/taxy/tree/main) - A reverse proxy server with built-in WebUI, supporting TCP/HTTP/TLS/WebSocket, written in Rust.
*   [Proxelar (⭐430)](https://github.com/emanuele-em/proxelar) - Rust-based Man in the Middle proxy, an early-stage project aimed at providing visibility into network traffic.
*   [diff.rs (⭐117)](https://github.com/xfbs/diff.rs) - Web application to render a diff between Rust crate versions. Implemented in Yew, runs fully in the browser as WebAssembly, [Live Demo](https://diff.rs).
*   [konnektoren.help](https://github.com/Konnektoren/konnektoren-web-game) - An interactive web application for learning German grammar, featuring gamified challenges and a map-based interface. [Web App](https://konnektoren.help)
*   [layout-viewer](https://prideout.net/layout-viewer) - Examine layouts of integrated circuits with zoom and pan controls.

## Templates

*   [Create Yew App (⭐165)](https://github.com/jetli/create-yew-app) - Set up a modern Yew web app by running one command, `npx create-yew-app my-app`.
*   [yew-wasm-pack-template (⭐119)](https://github.com/yewstack/yew-wasm-pack-template) - A template for starting a Yew project to be used with wasm-pack.
*   [yew-wasm-pack-minimal (⭐112)](https://github.com/yewstack/yew-wasm-pack-minimal) - A minimal template for starting a Yew project using wasm-bindgen and wasm-pack.
*   [yew-parcel-template (⭐112)](https://github.com/spielrs/yew-parcel-template) - Awesome Yew with Yew-Router and Parcel application.
*   [yew-template-for-github-io (⭐25)](https://github.com/Ja-sonYun/yew-template-for-github-io) - Directly deployable Template of yew project for github.io, using tailwind and webpack for css, trunk for build and serve.
*   [tailwindcss-yew-template (⭐17)](https://github.com/vvcaw/tailwindcss-yew-template) - Simple layout for using Tailwindcss with Yew.
*   [axum-yew-setup (⭐142)](https://github.com/rksm/axum-yew-setup) - A starter project that sets up Axum and Yew for full stack Rust web apps.
*   [rust-yew-axum-tauri-desktop (⭐148)](https://github.com/jetli/rust-yew-axum-tauri-desktop) - Rust + Yew + Axum + Tauri, full-stack Rust development for Desktop apps.
*   [Yew PWA Minimal (⭐60)](https://github.com/fkohlgrueber/yew-pwa-minimal) - A minimal Progressive Web App using Yew.
*   [Yew HTTP Starter (⭐4)](https://github.com/LeTurt333/yew_http_starter) - Yew template with a simple HTTP message & useful helper comments.
*   [Yew minimlistic template (⭐0)](https://github.com/averichev/yew-starter-template) - A minimalistic template for quickly starting a project on yew.

## Crates

### Component Libraries

*   [yew-mdc (⭐64)](https://github.com/dungeonfog/yew-mdc) - Material Design Components for the Yew framework.
*   [muicss-yew (⭐37)](https://github.com/AlephAlpha/muicss-yew) - MUI-CSS Components for Yew framework.
*   [yew-bulma (⭐21)](https://github.com/kellpossible/yew-bulma) - A Rust library providing components based on the bulma css library for projects using Yew.
*   [material-yew (⭐232)](https://github.com/hamza1311/material-yew) - Yew wrapper for Material Web Components.
*   [Yewprint (⭐452)](https://github.com/yewprint/yewprint) - Port of blueprintjs.com to Yew.
*   [ybc (⭐255)](https://github.com/thedodd/ybc) - A Yew component library based on the Bulma CSS framework.
*   [patternfly-yew (⭐159)](https://github.com/ctron/patternfly-yew) - Patternfly components for Yew.
*   [yew-feather (⭐19)](https://github.com/pedrodesu/yew-feather) - Feather Icons components for Yew.
*   [tailwind-yew-builder (⭐76)](https://github.com/matiu2/tailwind-yew-builder) - Builds Tailwind CSS for Yew using docker-compose. Also supports Trunk.
*   [yew-components (⭐62)](https://github.com/angular-rust/yew-components) - Material Design Components for the Yew framework.
*   [yew-chart (⭐65)](https://github.com/titanclass/yew-chart) - A Yew-based charting library that provides SVG based components for rendering charts.
*   [tailyew (⭐18)](https://github.com/fuzzycloud/tailyew) - Yew wrapper around DaisyUI (tailwindcss based) components.
*   [yew-duskmoon-ui (⭐5)](https://github.com/gsmlg-dev/yew-duskmoon-ui) - Duskmoon UI Component Library. This package use `stylist` to embbed css in components, so no extra CSS file is needed. [Live Demo](https://gsmlg-dev.github.io/yew-duskmoon-ui/).
*   [yew-bootstrap (⭐40)](https://github.com/isosphere/yew-bootstrap) - A Yew wrapper for the Bootstrap 5 component library.
*   [Zu (⭐6)](https://github.com/RustVis/zu) - Yew web components, implementing Material Design.
*   [yew-nav-link (⭐1)](https://github.com/RAprogramm/yew-nav-link) - A navigational link that is aware of its active state based on the current route in the application.
*   [Rust Lucide](https://lucide.rustforweb.org) - Yew port of Lucide, a beautiful & consistent icon toolkit made by the community.
*   [Rust Radix](https://radix.rustforweb.org) - Yew port of Radix, a library of components, icons, colors, and templates for building high-quality, accessible UI.
*   [Rust shadcn/ui](https://shadcn-ui.rustforweb.org) - Yew port of shadcn/ui, a library of beautifully designed components that you can copy and paste into your apps.

### Components

*   [Yew Form (⭐96)](https://github.com/jfbilodeau/yew_form) - Components to simplify handling forms with Yew.
*   [yew-component-size (⭐4)](https://github.com/AircastDev/yew-component-size) - A Yew component that emits events when the parent component changes width/height.
*   [yew-virtual-scroller (⭐4)](https://github.com/AircastDev/yew-virtual-scroller) - A Yew component for virtual scrolling / scroll windowing.
*   [yew-oauth2 (⭐46)](https://github.com/ctron/yew-oauth2/) - A plain Yew OAuth2/OpenIDConnect component, not tied to any CSS framework.
*   [yew-scroll-area (⭐4)](https://github.com/MatchaChoco010/yew-scroll-area) - Custom scroll area for Yew.

### Hooks

*   [yew-hooks (⭐170)](https://github.com/jetli/yew-hooks) - Custom Hooks library for Yew, inspired by [streamich/react-use (⭐43k)](https://github.com/streamich/react-use) and [alibaba/hooks (⭐14k)](https://github.com/alibaba/hooks).
*   [yew-side-effect (⭐5)](https://github.com/futursolo/yew-side-effect) - Reconcile Side Effects in Yew Applications, inspired by [react-side-effect (⭐1.2k)](https://github.com/gaearon/react-side-effect) and [react-helmet (⭐17k)](https://github.com/nfl/react-helmet).
*   [Bounce (⭐101)](https://github.com/bounce-rs/bounce) - The uncomplicated state management library for Yew, inspired by [Redux (⭐61k)](https://github.com/reduxjs/redux) and [Recoil (⭐20k)](https://github.com/facebookexperimental/Recoil).
*   [yewv (⭐11)](https://github.com/yewv/yewv) - A lightning fast state management module for Yew built with performance and simplicity as a first priority.

### Javascript Library Ports

*   [Plotly.rs (⭐1.3k)](https://github.com/igiagkiozis/plotly) - Rust bindings for the popular [Plotly](https://plotly.com/javascript/) charting library.
*   [ag-grid-rs (⭐15)](https://github.com/mfreeborn/ag-grid-rs) - Rust bindings for the [AG Grid](https://www.ag-grid.com/javascript-data-grid/) datatable library.
*   [popper-rs (⭐5)](https://github.com/ctron/popper-rs/) - [Popper JS](https://popper.js.org/) bindings for Rust.

### Utils

*   [Yewdux (⭐324)](https://github.com/intendednull/yewdux) - Redux-like state containers for Yew apps.
*   [reacty\_yew (⭐54)](https://github.com/hobofan/reacty_yew) - Generate Yew components from React components via Typescript type definitions.
*   [styled-yew (⭐35)](https://github.com/IcyDefiance/styled-yew) - CSS in Rust, similar to styled-components, but for Yew.
*   [stylist-rs (⭐379)](https://github.com/futursolo/stylist-rs) - A CSS-in-Rust styling solution for WebAssembly Applications.
*   [Yew Interop (⭐43)](https://github.com/Madoshakalaka/yew-interop) - Load JavaScript and CSS asynchronously in Yew.
*   [Tailwind RS (⭐114)](https://github.com/oovm/tailwind-rs) - Tailwind style tracer in rust, JIT + AOT interpreter.
*   [yew-style-in-rs (⭐23)](https://github.com/MatchaChoco010/yew-style-in-rs) - Scoped CSS in Rust for Yew.
*   [yew\_icons (⭐42)](https://github.com/finnbear/yew_icons) - Easily include a variety of svg icons(Feather/Font Awesome/Octicons) into your Yew app.
*   [Yew-Template (⭐40)](https://github.com/INSAgenda/yew-template) - A crate for separating HTML and Rust code when using Yew.
*   [yew-nested-router (⭐8)](https://github.com/ctron/yew-nested-router) - A router that supported nesting, with Yew 0.20.
*   [turf (⭐80)](https://github.com/myFavShrimp/turf) - Macro based compile-time SCSS transpilation, CSS minification, and class name uniquification toolchain inspired by CSS modules.
*   [browser-panic-hook (⭐7)](https://github.com/ctron/browser-panic-hook) - A panic handler for browser environments, allowing to fail in an end-user friendly way.
*   [Rust Floating UI](https://floating-ui.rustforweb.org/) - Floating UI is a library that helps you create "floating" elements such as tooltips, popovers, dropdowns, and more.

### Wasm

*   [wasm-bindgen (⭐8.1k)](https://github.com/rustwasm/wasm-bindgen) - Facilitating high-level interactions between WebAssembly modules and JavaScript.
*   [stdweb (⭐3.4k)](https://github.com/koute/stdweb) - Provides Rust bindings to the Web APIs and to allow a high degree of interoperability between Rust and JavaScript.
*   [tauri-sys (⭐105)](https://github.com/JonasKruckenberg/tauri-sys) - Raw bindings to the Tauri API for projects using wasm-bindgen.

### Frameworks

*   [stackable (⭐22)](https://github.com/futursolo/stackable) - A framework experience for Yew.

## Tooling

*   [wasm-pack (⭐6.5k)](https://github.com/rustwasm/wasm-pack) - Your favorite Rust -> WebAssembly workflow tool.
*   [wasm-pack-action (⭐50)](https://github.com/jetli/wasm-pack-action) - Github action to install `wasm-pack` by downloading the executable to speed up CI/CD.
*   [wasm-bindgen-action (⭐12)](https://github.com/jetli/wasm-bindgen-action) - Github action to install `wasm-bindgen` by downloading the executable to speed up CI/CD.
*   [cargo-web (⭐1.1k)](https://github.com/koute/cargo-web) - A Cargo subcommand for the client-side Web.
*   [Trunk (⭐3.8k)](https://github.com/thedodd/trunk) - Build, bundle & ship your Rust Wasm application to the web.
*   [trunk-action (⭐32)](https://github.com/jetli/trunk-action) - Github action to install `Trunk` by downloading the executable to speed up CI/CD.
*   [wabt (⭐7.2k)](https://github.com/WebAssembly/wabt) - The WebAssembly Binary Toolkit, for the `wasm-strip` and `wasm-objdump` tools to reduce .wasm file size.
*   [binaryen (⭐7.7k)](https://github.com/WebAssembly/binaryen) - Compiler infrastructure and toolchain library for WebAssembly, for the `wasm-opt` tool to reduce .wasm file size.
*   [Tauri (⭐90k)](https://github.com/tauri-apps/tauri) - Tauri is a framework for building tiny, blazingly fast binaries for all major desktop platforms. Developers can integrate any front-end framework that compiles to HTML, JS and CSS for building their user interface. The backend of the application is a rust-sourced binary with an API that the front-end can interact with.
*   [yew-fmt (⭐25)](https://github.com/schvv31n/yew-fmt) - A configurable extension to `rustfmt` for formatting Yew HTML.

## Articles

*   [Let's Build a Rust Frontend with Yew](https://dev.to/deciduously/lets-build-a-rust-frontend-with-yew---part-1-3k2o)
*   [How to use Rust Yew (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20Rust%20Yew.md)
*   [How to use a modal in Rust (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20a%20modal%20in%20Rust.md)
*   [How to use routers in Rust Frontend (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20routers%20in%20Rust%20Frontend.md)
*   [How to modulize your Rust Frontend (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20modulize%20your%20Rust%20Frontend.md)
*   [How to use NPM packages with Rust Frontend (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20NPM%20packages%20with%20Rust%20Frontend.md)
*   [How to use markdown with Rust Frontend (⭐3)](https://github.com/steadylearner/blog/blob/master/posts/Rust/How%20to%20use%20markdown%20with%20code%20snippets%20in%20Rust%20Frontend.md)
*   [Fullstack Rust with Yew (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/Fullstack%20Rust%20with%20Yew.md)
*   [How to write Full Stack Rust code (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20write%20Full%20Stack%20Rust%20code.md)
*   [How to render a YouTube vlog with Rust Yew fetch API (⭐3)](https://github.com/steadylearner/blog/blob/master/posts/Rust/How%20to%20render%20a%20YouTube%20vlog%20with%20%20Rust%20Yew%20fetch%20API.md)
*   [How to render blog posts with Rust Yew mounted API (⭐3)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20render%20blog%20posts%20with%20Rust%20Yew%20mounted%20API.md)
*   [A Web Application completely in Rust](https://medium.com/@saschagrunert/a-web-application-completely-in-rust-6f6bdb6c4471)
*   [Yew - Rust & WebAsse-frontend framework](https://sudonull.com/post/11627-Yew-Rust-WebAsse-frontend-framework)
*   [Create a desktop app in Rust using Tauri and Yew](https://dev.to/stevepryde/create-a-desktop-app-in-rust-using-tauri-and-yew-2bhe)
*   [A code walkthrough video of Yew with a real-world app with Christopher Hunt and Kiki Carter](https://www.youtube.com/watch?v=ilrGIJGdqRo)
*   [Adding Tailwind to Yew](https://mikekrisher.com/writings/yew_and_tailwind)

## Courses

*   [full-stack-todo-rust-course (⭐250)](https://github.com/brooks-builds/full-stack-todo-rust-course) - Full stack rust course including course for Yew.

## Books

*   [The WebAssembly Book](https://rustwasm.github.io/docs/book/) - Working with the web and producing .wasm files.
*   [The wasm-bindgen Guide](https://rustwasm.github.io/docs/wasm-bindgen/) - How to bind Rust and JavaScript APIs.
*   [The wasm-pack Guide](https://rustwasm.github.io/docs/wasm-pack/) - How to build and work with rust-generated WebAssembly.
*   [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) - Includes a chapter `Advanced JavaScript Integration with Yew` on creating an app with Yew.
*   [Creative Projects for Rust Programmers](https://www.oreilly.com/library/view/creative-projects-for/9781789346220/) - Chapter 5, `Creating a Client-Side WebAssembly App Using Yew`.

## Alternatives

Yew team love to share ideas with other projects and believe we can all help each other reach the full potential of this exciting new technology.

*   [Draco (⭐301)](https://github.com/utkarshkukreti/draco) - A Rust library for building client side web applications with WebAssembly.
*   [Percy (⭐2.3k)](https://github.com/chinedufn/percy) - A modular toolkit for building isomorphic web apps with Rust + WebAssembly.
*   [Sauron (⭐2k)](https://github.com/ivanceras/sauron) - Sauron is an HTML web framework for building web-apps.
*   [Seed (⭐3.8k)](https://github.com/seed-rs/seed) - A Rust framework for creating web apps.
*   [Smithy (⭐349)](https://github.com/rbalicki2/smithy) - A framework for building WebAssembly apps in Rust.
*   [Dioxus (⭐26k)](https://github.com/DioxusLabs/dioxus) - Elegant React-like library for building user interfaces for desktop, web, mobile, SSR, liveview, and more.
*   [Sycamore (⭐3k)](https://github.com/sycamore-rs/sycamore) - A reactive library for creating web apps in Rust and WebAssembly.
*   [Leptos (⭐18k)](https://github.com/leptos-rs/leptos) - Build fast web applications with Rust.

## Related lists

*   [Awesome Rust and WebAssembly (⭐656)](https://github.com/rustwasm/awesome-rust-and-webassembly) - A list of awesome Rust and WebAssembly projects, libraries, tools, and resources.
*   [Awesome WebAssembly (⭐9.1k)](https://github.com/mbasso/awesome-wasm) - Collection of awesome things regarding WebAssembly ecosystem.
*   [Awesome Rust (⭐49k)](https://github.com/rust-unofficial/awesome-rust) - A curated list of Rust code and resources.

