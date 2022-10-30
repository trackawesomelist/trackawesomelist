# Progressive Enhancement Resources Overview

Resources on Progressive Enhancement. From concept and strategies to feature detection & testing methods. Complete with a list of (code) examples.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/jbmoelker/progressive-enhancement-resources/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 jbmoelker/progressive-enhancement-resources](https://github.com/jbmoelker/progressive-enhancement-resources) · ⭐ 91 · 🏷️ Front-End Development

[ [Daily](/content/jbmoelker/progressive-enhancement-resources/README.md) / [Weekly](/content/jbmoelker/progressive-enhancement-resources/week/README.md) / Overview ]

---

# Progressive Enhancement Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A comprehensive collection of resources on Progressive Enhancement. From concept and strategies to feature detection and testing methods. Complete with a list of (code) examples.

## Contents

*   [The Concept](#the-concept)
*   [Strategies](#strategies)
*   [Feature Detection](#feature-detection)
*   [Support Tables](#support-tables)
*   [Testing Methods](#testing-methods)
*   [Examples](#examples)
*   [Related Articles](#related-articles)

## The Concept

[Progressive Enhancement](https://en.wikipedia.org/wiki/Progressive_enhancement) means gradually improving the user experience after verifying the target environment (e.g. browser) is capable of it. Start with content and ensure you maintain functionality & accessibility.

*   [Progressive Enhancement: It's about the content](http://cognition.happycog.com/article/progressive-enhancement-its-about-the-content) - Sharing content is the core of the web. Progressive Enhancement ensures access to content.
*   [The Role of Enhancement in Web Design](https://www.nngroup.com/articles/enhancement/) - From the concept of enhancement to the criteria and rules for enriching the user interface.
*   [Understanding Progressive Enhancement](http://alistapart.com/article/understandingprogressiveenhancement) - Apply technologies in an intelligent way, layer-upon-layer, to craft an amazing experience.
*   [Designing with Progressive Enhancement](https://www.filamentgroup.com/dwpe/) - *The book* (400+ pages) on Progressive Enhancement.
*   [Adaptive Web Design](http://adaptivewebdesign.info/2nd-edition/) - Book on Progressive Enhancement from content to design and interaction.
*   [Detecting (HTML5) features](http://diveinto.html5doctor.com/detect.html) - Intro to different feature detection techniques with examples and demos.
*   [Progressive Web Apps](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/) - Enhancing web sites into native-like apps (progressive, not hybrid).

## Strategies

You can apply Progressive Enhancement in different ways:

*   [The Content-out Approach](https://articles.uie.com/progressive_enhancement/) - Provide wide access to content without technological restrictions.
*   [Make the page usable with only HTML](https://www.gov.uk/service-manual/technology/using-progressive-enhancement#make-the-page-usable-with-only-html) - This sets the baseline for every device and browser.
*   [Test Driven Progressive Enhancement](http://alistapart.com/article/testdriven) - Core functional experience enhanced after testing capabilities.
*   [Cut the mustard](http://responsivenews.co.uk/post/18948466399/cutting-the-mustard) - Set a threshold for collection of enhancements.
*   [Grade components, not browsers](https://www.filamentgroup.com/lab/grade-the-components.html) - Component level feature tests and enhancements.
*   [Feature vs Browser vs Form factor detection](http://www.html5rocks.com/en/tutorials/detection/) - As different strategies to tune your app to its environment.
*   [Server-side device detection](https://www.smashingmagazine.com/2014/07/server-side-device-detection-with-javascript/) - Use user-agent and other HTTP header info combined with a device database to conditionally serve files.
*   [Writing polyfills](https://addyosmani.com/blog/writing-polyfills/) - If your baseline is still too high for some browsers, consider [polyfills](https://remysharp.com/2010/10/08/what-is-a-polyfill) (aka [Regressive Enhancement](https://twitter.com/SlexAxton/status/25600963629)).
*   [Application Shell Architecture](https://medium.com/google-developers/instant-loading-web-apps-with-an-application-shell-architecture-7c0c2f10c73) - Setup for instant loading web apps.

## Feature Detection

Before you try to enhance the experience, you need to ensure the environment is capable of the enhancement. You test this by performing feature detections:

*   [CSS feature queries](https://www.sitepoint.com/an-introduction-to-css-supports-rule-feature-queries/) ([`CSS.supports()`](https://developer.mozilla.org/en/docs/Web/API/CSS/supports) & [`@supports()`](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)) - Natively test if specific CSS feature is supported using JS method or CSS declaration.
*   [Feature Detect ES6](https://www.npmjs.com/package/feature-detect-es6) - Detect which ES2015 features are available.
*   [SVG requiredFeatures](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/requiredFeatures) - Render SVG elements only if their `[requiredFeatures]` evaluate to true.
*   [Modernizr](https://modernizr.com/) - Extensive feature detection suite (supports custom builds).
*   [Feature.js](http://featurejs.com/) - Lightweight feature detection suite.
*   [Conditioner.js](http://conditionerjs.com/) - Conditionally load JS modules based on directives in HTML attributes.
*   [EnhanceJS](https://www.filamentgroup.com/lab/introducing-enhancejs-smarter-safer-apply-progressive-enhancement.html) - Lets you asynchronously load CSS & JS after a set pre-defined feature tests.

## Support Tables

Different environments (platforms, browsers, versions) have different capabilities. Support tables tell you what capabilities each environment has. Knowing the level of support can help you weigh an enhancement against the effort and impact of its implementation.

*   [The Web Platform](https://platform.html5.org/) - Overview of browser technologies with links to docs and test suites.
*   [Can I use ...?](http://caniuse.com/) - Compare feature implementations and limitations across desktop & mobile browsers.
*   [I want to use ...](http://www.iwanttouse.com/) - Figure out the browser support of combinations of features.
*   [HTML5 Test](http://html5test.com/) - Test and compare HTML5 feature support across browsers.
*   [CSS3 Test](http://css3test.com/) - Fine-grained tests for CSS3 feature support of your current browser.
*   [Accessibility Support](https://a11ysupport.io/) - Compare accessibility support of HTML elements and ARIA roles across browsers & assistive technologies.
*   [State of Web Type](https://github.com/bramstein/stateofwebtype) - Support tables for type and typographic features on the web.
*   [Font Family Reunion](http://fontfamily.io/) - Compatibility tables for default local (system) fonts.
*   [HTML5 Accessibility](http://html5accessibility.com/) - Compare feature support of HTML5 tags, input types and properties across major browsers.
*   [WAI-ARIA Screen reader compatibility](https://www.powermapper.com/tests/screen-readers/aria/) - ARIA roles and attributes support for different screen reader and browser combinations.
*   [What web can do today](https://whatwebcando.today/) - Lists and checks modern web APIs like access to device system, sensors and actuators.
*   [HTML5 Worker test](https://nolanlawson.github.io/html5workertest/) - Compare which APIs are supported in Web Workers and Service Workers across browsers.
*   [HTML5 Please](http://html5please.com/) - Explore features with recommendations and links to polyfills.
*   [API Catalog](https://developer.microsoft.com/en-us/microsoft-edge/platform/catalog/) - Lets you compare implementation of API specifications in major desktop browsers.
*   [Kangax's ECMAScript compatibility table](http://kangax.github.io/compat-table/) - Overview of JavaScript feature support across browsers and other runtimes.
*   [Node compatibility table](http://node.green/) - Overview of JavaScript feature support across NodeJS versions.
*   [Is service worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - Overview of support for all features involved in the core technology behind Progressive Web Apps.
*   [Is PWA ready?](https://ispwaready.toxicjohann.com/) - Overview of support for the core and related technologies behind Progressive Web Apps for both popular global and many Chinese browsers.
*   [Is WebRTC ready yet?](http://iswebrtcreadyyet.com/) - Overview of support for the different browser features behind real time communication.
*   [Is WebVR ready?](https://iswebvrready.org/) - Overview of support of different browser features behind WebVR including display, gamepad, audio and speech APIs.
*   [Is Houdini ready yet?](https://ishoudinireadyyet.com/) - Overview of support for Houdini (low-level APIs exposing parts of the CSS rendering engine) across browsers.
*   [Chrome Platform Status](https://www.chromestatus.com/features)
*   [Edge Platform Status](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/)
*   [Firefox Platform Status](https://platform-status.mozilla.org/)
*   [Webkit Platform Status](https://webkit.org/status/) (Safari)
*   [MDN Compatibility tables](https://developer.mozilla.org/en-US/docs/MDN/Contribute/Structures/Compatibility_tables) - MDN's web technology documentation has a browser compatibility table end the end of each article.
*   [MDN Browser Compat Data](https://github.com/mdn/browser-compat-data) - npm module powering the MDN Compatibility tables.
*   [Device Bugs & Quirks](https://github.com/scottjehl/Device-Bugs) - Crowd sourced collection of weird HTML, CSS, and JS quirks in mobile devices, which you won't find in the other support tables.
*   [Can I Email?](https://www.caniemail.com/) - Support tables for HTML and CSS in emails. Inspired by [Can I use](http://caniuse.com/).
*   [Project Fugu API tracker](https://fugu-tracker.web.app/) - Browser support status overview of web API's filling the "app gap".

## Testing Methods

With progressive enhancement you support different experiences in different environments. These are some ways to test all these variations:

*   [Open Device Lab](https://opendevicelab.com/) - Lets you *test manually on actual devices* (for free).
*   [Text browsers](https://en.wikipedia.org/wiki/Text-based_web_browser) - Good way to test if your content is accessible at the baseline. Try [Lynx](http://lynx.browser.org/) for example.
*   [Testing in Opera Mini](https://dev.opera.com/articles/making-sites-work-opera-mini/#testing-in-opera-mini) - Download the app, emulate on desktop, setup to test local websites. (Opera Mini accounts for over 5% browser usage world wide)
*   [cURL](https://curl.haxx.se/docs/manual.html) - Web page to see the pre-rendered source code of a page.
*   [Browserling](https://www.browserling.com/) - Lets you manually test web pages in different versions of browsers on Windows and Android platforms.
*   [Run Internet Explorer using Virtual Machines](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/mac/) - To test IE browsers on other platforms.
*   [Device emulators and simulators](https://developers.google.com/web/tools/chrome-devtools/iterate/device-mode/testing-other-browsers?hl=en#device-emulators-and-simulators)
*   [Configure *Desired Capabilities* in Selenium](https://github.com/SeleniumHQ/selenium/wiki/DesiredCapabilities) - Run automated browser tests in different scenarios.
*   Continuously run automated tests in different browsers using [BrowserStack](https://www.browserstack.com/), [Saucelabs](https://saucelabs.com/) or other alternatives.
*   [Lighthouse](https://github.com/GoogleChrome/lighthouse) - Audit and meassure performance of Progressive Web Apps (via cli or [Chrome extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)).
*   [Progressive Enhancement checklist (1st edition, HTML)](http://adaptivewebdesign.info/1st-edition/read/chapter-6.html#the-progressive-enhancement-checklist), [Checklist of 2nd edition (PDF)](http://adaptivewebdesign.info/2nd-edition/checklist.pdf) - Actionable list to check you've applied Progressive Enhancement best practices. Part of [Adaptive Web Design book](http://adaptivewebdesign.info/).
*   [CSS Feature Toggles](https://chrome.google.com/webstore/detail/css-feature-toggles/aeinmfddnniiloadoappmdnffcbffnjg) - Chrome DevTools extension to toggle support of selected CSS features for testing progressive enhancement fallbacks.

## Examples

### Custom Form Elements

*   [Fancy radio buttons](https://www.sitepoint.com/replacing-radio-buttons-without-replacing-radio-buttons/) - Based on HTML radio buttons, visually enhanced using CSS pseudo classes and elements.
*   [Checkboxes & radio buttons](https://www.filamentgroup.com/dwpe/checkbox-radiobutton/) - With custom focus, hover and checked state. Enhanced asynchronously.
*   [Toggle switch](https://ghinda.net/css-toggle-switch/) - Checkbox or radios, visually enhanced to sliding toggle switches using CSS only.
*   [5-star rating](http://lea.verou.me/2011/08/accessible-star-rating-widget-with-pure-css/) - Based on HTML radio buttons, visually enhanced using CSS pseudo classes and elements.
*   [jQuery slider](https://github.com/filamentgroup/jQuery-Slider) - Accessible, custom slider widget based on a standard HTML select.
*   [jQuery custom file input](https://www.filamentgroup.com/lab/jquery-custom-file-input-book-designing-with-progressive-enhancement.html) - Article and library.
*   [React isomorphic form](https://github.com/ghengeveld/react-isomorphic-form/) - Set of React form components which can be pre-rendered & handled server-side. They are enhanced client-side without losing state.

### Data Visualisations

*   [Timeline](https://css-tricks.com/progressive-enhancement-data-visualizations/) - From definition list to SVG illustration (article with demos).
*   [Charts](https://www.filamentgroup.com/lab/update-to-jquery-visualize-accessible-charts-with-html5-from-designing-with.html) - From data table to themed charts using HTML5 canvas (article and library).

### Images

*   [Responsive Carousel](http://filamentgroup.github.io/responsive-carousel/test/functional/fade-auto.html) - List of images enhanced into responsive carousel with various behaviour options.
*   [Lazy Progressive Enhancement](https://github.com/tvler/lazy-progressive-enhancement) - Lazy load images inside `<noscript>` tags. (note: Evergreen browsers only)

### Menus

*   [Progressive hamburger menu](http://heydonworks.com/practical_aria_examples/#hamburger) - List of links in footer enhanced to off-canvas menu.

### Page Navigation

Asynchronously fetch and transition between static pages using ajax and `history.pushState`:

*   [Barba.js](http://barbajs.org/) - Add page transitions with event hooks, cache and prefetch support.
*   [SmoothState.js](https://github.com/miguel-perez/smoothState.js) - Add page transitions with event hooks, cache and prefetch support. (requires jQuery).
*   [jquery-pjax](https://github.com/defunkt/jquery-pjax) - Add page transitions with support for multiple containers / content slots (requires jQuery).
*   [MoOx/pjax](https://github.com/MoOx/pjax) - Similar tot jquery-pjax, but without the jQuery dependency.
*   [Turbolinks](https://github.com/turbolinks/turbolinks) - Add page transitions with event hooks and cache support. Has adapters to bind to native navigation controls on iOS and Android.

## Related Articles

*   [Make the web work for everyone](https://hacks.mozilla.org/2016/07/make-the-web-work-for-everyone/) - Plea to developers to consider browser differences and build a resilient web.
*   [How many people are missing out on JavaScript enhancement?](https://gds.blog.gov.uk/2013/10/21/how-many-people-are-missing-out-on-javascript-enhancement/) - Research on why in 1.1% of page visits JavaScript isn't loaded.

***

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

[Jasper Moelker](https://twitter.com/jbmoelker) waives all rights to this work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

