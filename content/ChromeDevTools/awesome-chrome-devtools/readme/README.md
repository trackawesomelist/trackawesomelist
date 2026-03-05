# Awesome Chrome Devtools Overview

Awesome tooling and resources in the Chrome DevTools & DevTools Protocol ecosystem

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/ChromeDevTools/awesome-chrome-devtools/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 ChromeDevTools/awesome-chrome-devtools](https://github.com/ChromeDevTools/awesome-chrome-devtools) · ⭐ 6.9K · 🏷️ Front-End Development

[ [Daily](/content/ChromeDevTools/awesome-chrome-devtools/README.md) / [Weekly](/content/ChromeDevTools/awesome-chrome-devtools/week/README.md) / Overview ]

---

# Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

## Contents

*   [Learning](#learning)
*   [DevTools tooling and ecosystem](#devtools-tooling-and-ecosystem)
*   [Chrome DevTools Protocol](#chrome-devtools-protocol)
*   [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
*   [Applications](#applications)
*   [DevTools Extensions](#devtools-extensions)
*   [Alumni](#alumni)

***

## Learning

*   [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.
*   [DevTools Tips](https://devtoolstips.org/) - Collection of illustrated tips as mini tutorials.
*   [Can I DevTools?](https://www.canidev.tools/) - Various workflows, documented. Also a weekly tips & tricks [newsletter](https://canidevtools.substack.com/).
*   [Web cheatcodes](https://codepo8.github.io/web-cheatcodes/) - Browser developer tools for non-developers.
*   [Dear Console](https://codepo8.github.io/dearconsole) - A collection of snippets to use in the browser console.
*   [Chrome Secret Menus (⭐58)](https://github.com/sparkyrider/chrome-secret-menus) - Comprehensive guide to internal pages and diagnostic tools in Chrome.

***

## DevTools tooling and ecosystem

### Object formatting

*   [immutable-devtools (⭐672)](https://github.com/andrewdavey/immutable-devtools) - Custom formatter for Immutable-js values.

### Network Inspection

*   [betwixt (⭐4.6k)](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel.
*   [Weer](https://weerdbg.com/) - A HTTP protocol debugger **(closed source)**

### CPU profile

*   [call-trace](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts.
*   [cpuprofilify (⭐169)](https://github.com/thlorenz/cpuprofilify) - Converts output of various profiling/sampling tools to the `.cpuprofile` format.
*   [Wishbone Python framework](https://wishbone.readthedocs.io/en/latest/misc/profiling.html) - Profiling data can export as `.cpuprofile`.

### Multimedia

*   [snapline (⭐401)](https://github.com/pmdartus/snapline) - Converts timeline screenshots to gif.

### Timeline, Tracing & Profiling

*   [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

### Chrome Debugger integration with Editors

*   [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - Breakpoint debugging in VS Code.
*   [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools) - Elements panel inside VS Code.
*   [ChromeREPL (⭐356)](https://github.com/acarabott/ChromeREPL) - Within Sublime Text, use the Chrome console.
*   [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - JavaScript Breakpoint debugging right in Sublime Text.
*   [WebStorm/JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

***

## Chrome DevTools Protocol

*   [ChromeDevTools/devtools-protocol (⭐1.4k)](https://github.com/chromedevtools/devtools-protocol) - **Canonical location of the protocol JSON**. Issue tracker for protocol bugs. TypeScript types.
*   [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events.

### Developing with the protocol

*   [chrome-remote-interface Wiki (⭐4.5k)](https://github.com/cyrus-and/chrome-remote-interface/wiki) - Many useful recipes.
*   [Chrome Protocol Proxy (⭐246)](https://github.com/wendigo/chrome-protocol-proxy) - Tool for debugging clients using devtools protocol.

### The big two automation libraries

*   [Puppeteer (⭐94k)](https://github.com/GoogleChrome/puppeteer/) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol. See also [awesome-puppeteer (⭐2.5k)](https://github.com/transitive-bullshit/awesome-puppeteer).
*   [Playwright (⭐83k)](https://github.com/microsoft/playwright) - Library to automate Chromium, Firefox and WebKit with a single API. Available for Node.js, Python, .Net, Java. See also [awesome-playwright](https://github.com/mxschmitt/awesome-playwright).

### Libraries for driving the protocol (or a layer above)

*   JavaScript/Node.js: [chrome-remote-interface (⭐4.5k)](https://github.com/cyrus-and/chrome-remote-interface)
*   TypeScript/Node.js: [chrome-debugging-client (⭐134)](https://github.com/TracerBench/chrome-debugging-client)
*   TypeScript/Node.js: [noice-json-rpc](https://www.npmjs.com/package/noice-json-rpc) - A proxy-based implementation to expose the CDP as its API.
*   TypeScript/Node.js: [Taiko (⭐3.7k)](https://github.com/getgauge/taiko/)
*   Rust: [Rust Headless Chrome (⭐24)](https://github.com/atroche/rust-headless-chrome/)
*   Java: [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)
*   Java: [jvppeteer (⭐804)](https://github.com/fanyong920/jvppeteer)  - Headless Chrome For Java
*   Python: [PyCDP (⭐137)](https://github.com/hyperiongray/python-chrome-devtools-protocol) - Pure-Python, sans-IO wrappers. See also the [Trio CDP driver (⭐71)](https://github.com/hyperiongray/trio-chrome-devtools-protocol)
*   Python: [chromewhip (⭐120)](https://github.com/chuckus/chromewhip) - drop-in replacement for the `splash` service
*   Python: [pyppeteer (⭐3.9k)](https://github.com/pyppeteer/pyppeteer) - Puppeteer port
*   Python: [ChromeController (⭐228)](https://github.com/fake-name/ChromeController) - high-level browser mgmt
*   Go: [chromedp (⭐13k)](https://github.com/chromedp/chromedp) - High-level actions and tasks for driving browsers
*   Go: [cdp (⭐784)](https://github.com/mafredri/cdp)
*   Go: [gcd (⭐187)](https://github.com/wirepair/gcd)
*   Go: [godet (⭐401)](https://github.com/raff/godet)
*   Go: [Rod (⭐6.7k)](https://github.com/go-rod/rod)
*   C#/.NET: [Puppeteer Sharp](https://github.com/hardkoded/puppeteer-sharp) - Puppeteer port
*   C#/dotnet: [chrome-dev-tools (⭐81)](https://github.com/BaristaLabs/chrome-dev-tools) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.
*   C#/.NET: [dotnet-chrome-protocol (⭐27)](https://github.com/seclerp/dotnet-chrome-protocol) - A runtime library and schema code generation tools for Chrome DevTools Protocol support in C#/.NET.
*   Ruby: [Ferrum](https://github.com/route/ferrum) - high-level API to control Chrome in Ruby
*   Ruby: [Cuprite (⭐1.4k)](https://github.com/machinio/cuprite) - Capybara driver
*   Kotlin: [chrome-reactive-kotlin (⭐76)](https://github.com/wendigo/chrome-reactive-kotlin) - reactive (rxjava 2.x), low-level client library in Kotlin
*   Kotlin: [chrome-devtools-kotlin (⭐58)](https://github.com/joffrey-bion/chrome-devtools-kotlin) - A coroutine-based client library, providing low-level CDP primitives and high-level extensions.
*   Clojure: [clj-chrome-devtools (⭐133)](https://github.com/tatut/clj-chrome-devtools) - The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
*   Clojure: [cuic (⭐38)](https://github.com/milankinen/cuic) - Providing a high-level API for UI test automation over the DevTools Protocol.
*   PHP: [chrome-devtools-protocol (⭐183)](https://github.com/jakubkulhan/chrome-devtools-protocol) - A PHP client library for the protocol.
*   PHP: [PuPHPeteer (⭐1.3k)](https://github.com/rialto-php/puphpeteer) - PHP bridge to node Puppeteer

### Browser Adapters

*   [devtools-remote-debugger (⭐409)](https://github.com/Nice-PLQ/devtools-remote-debugger) - Use devtools against a webpage; a CDP agent implemeted in client-side JS.
*   [Inspect](https://inspect.dev/) - Use devtools against iOS and Android, easily. Browser and Webviews. **(closed source)**

## Using DevTools frontend with other platforms

#### Android

*   [Facebook Stetho (⭐13k)](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools.
*   [j2v8-debugger (⭐93)](https://github.com/AlexTrotsenko/j2v8-debugger) - Debugging JavaScript running in [J2V8 (⭐2.6k)](https://github.com/eclipsesource/J2V8) with Chrome DevTools.

#### ClojureScript

*   [Dirac (⭐772)](https://github.com/binaryage/dirac) - Debugging of ClojsureScript.

#### iOS

*   [PonyDebugger (⭐5.9k)](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools.

#### Node.js

*   [ndb](https://github.com/GoogleChromeLabs/ndb) - An improved Node.js debugging experience with the DevTools Frontend.
*   [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+.
*   [thetool (⭐223)](https://github.com/sfninja/thetool) - CPU, memory, coverage, type profiling with Node.
*   [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.

#### Ruby

*   [ruby/debug (⭐1.3k)](https://github.com/ruby/debug) - Debugging functionality for Ruby.

***

## Applications

### Browsers

*   [BrowserBox](https://github.com/BrowserBox/BrowserBox) - Embed Chrome in a web page, largely powered by DevTools and supporting multiuser browsing, remote DevTools, audio, and documents like `.docx`, `.pdf`, and more.
*   [Puppetromium (⭐61)](https://github.com/dosyago/puppetromium) - A proof-of-concept web browser built with Puppeteer, written in Node.js, HTML and CSS, with 0% client-side JavaScript.

### Web Archivers and Indexers

*   [dn (⭐3.9k)](https://github.com/dosyago/dn) - Archive and index pages you browse for offline viewing and search, implemented using the `Fetch` domain's interceptions, and works with any Chromium-based browser.

***

## DevTools Extensions

### Accessibility (A11y)

*   [Chromelens](https://chromewebstore.google.com/detail/chromelens/idikgljglpfilbhaboonnpnnincjhjkd) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

### Workflow

*   [Clockwork](https://chromewebstore.google.com/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
*   [Emulated Device Lab](https://chromewebstore.google.com/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
*   [RailsPanel](https://chromewebstore.google.com/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
*   [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
*   [Ember.js Inspector](https://chromewebstore.google.com/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect Ember.js objects in your application.
*   [Vue.js Developer Tools](https://github.com/vuejs/vue-devtools) - Inspect Vue.js components and manipulate their data.
*   [Angular DevTools](https://chromewebstore.google.com/detail/angular-devtools/ienfalfjdbdpebioblfackkekamfmbnh) - Debugging and Profiling for Angular applications.
*   [Marionette Inspector](https://chromewebstore.google.com/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
*   [Backbone Debugger](https://chromewebstore.google.com/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
*   [App Inspector for Sencha](https://chromewebstore.google.com/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
*   [Redux Devtools](https://chromewebstore.google.com/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
*   [Three.js](https://chromewebstore.google.com/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
*   [Insight (⭐919)](https://github.com/3Dparallax/insight/) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
*   [BEM devtools](https://github.com/escaton/bem-chrome-devtools) - Inspect BEM entities expressed in `i-bem` framework.
*   [Metal.js Developer Tools](https://chromewebstore.google.com/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - Inspect the Metal component hierarchies.
*   [Web Component DevTools](https://chromewebstore.google.com/detail/web-component-devtools/gdniinfdlmmmjpnhgnkmfpffipenjljo) - Inspect, modify and observe Web Components on page.

### Themes

*   [DevTools Author](https://chromewebstore.google.com/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
*   [Zero Dark Matrix](https://chromewebstore.google.com/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.
*   [Material UI Theme](https://chromewebstore.google.com/detail/material-devtools-theme-c/jmefikbdhgocdjeejjnnepgnfkkbpgjo) - Provides various Material Design inspired themes.

### Performance

*   [sloth (⭐200)](https://github.com/denar90/sloth) - Chrome extension allows to enable and save CPU and network throttling for selected tabs.
*   [TracerBench](https://github.com/TracerBench/tracerbench) - A controlled performance benchmarking tool for web applications, providing clear, actionable and usable insights into performance deltas.

### Automation

*   [Puppeteer IDE (⭐241)](https://github.com/gajananpp/puppeteer-ide-extension) - Standalone Puppeteer playground in browser's developer tools.
*   [k6 browser](https://github.com/grafana/xk6-browser) - Browser automation and end-to-end web testing tool that interacts with browsers and collects frontend performance metrics.

## Alumni

Old projects, likely not maintained any longer… But still cool.

*   [Remote Debug Gateway (⭐95)](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once.
    *   Multiuser DevTools: [DevTools Remote (⭐701)](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser.
*   [DevTools Backend (⭐148)](https://github.com/christian-bromann/devtools-backend) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.
*   Python CDP driver: [pychrome](https://github.com/fate0/pychrome) - low level CDP transport handler
*   [ios-webkit-debug-proxy (⭐6.1k)](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP.
    *   [Remote Debug iOS WebKit adapter (⭐2.7k)](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP.
*   [IE Diagnostics Adapter (⭐572)](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 11 to CDP.
*   [go-debugger-devtools (⭐42)](https://github.com/allada/go-debugger-devtools)

