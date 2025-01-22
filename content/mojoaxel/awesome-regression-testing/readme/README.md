# Awesome Regression Testing Overview

🕶️ A curated list of resources around the topic: visual regression testing

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/mojoaxel/awesome-regression-testing/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 mojoaxel/awesome-regression-testing](https://github.com/mojoaxel/awesome-regression-testing) · ⭐ 2.2K · 🏷️ Testing

[ [Daily](/content/mojoaxel/awesome-regression-testing/README.md) / [Weekly](/content/mojoaxel/awesome-regression-testing/week/README.md) / Overview ]

---

# Awesome Visual Regression Testing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Curated list of awesome visual regression testing resources.

Regression testing is a type of software testing which verifies that software which was previously developed and tested still performs the same way after it was changed or interfaced with other software. The purpose of regression testing is to ensure that changes to the software have not introduced new faults.

## Foreword

This is intended to be an *incomplete* list of resources about visual regression testing. It is not tailored to a specific area or role (Developer/QA/UX-Designer). Note that this is for all areas of regression software testing *after* the code in question is written. For a awesome list on general software testing see e.g. [awesome-testing (⭐1.9k)](https://github.com/TheJambo/awesome-testing).

Finally, I'm sure everyone who reads this list has one thing they want to add. Please read the [How to Contribute](https://github.com/mojoaxel/awesome-regression-testing/blob/master/README.md/.github/CONTRIBUTING.md) page and **Feel free to add to the list!!**. If you think this is helpful **Please give a Star ⭐️**.

## Contents

*   [General information](#general-information)
*   [Browser automation](#browser-automation)
*   [Tools and frameworks](#tools-and-frameworks)
*   [Online services](#online-services)
*   [Blog posts](#blog-posts)
*   [Slideshows, talks and videos](#slideshows-talks-and-videos)
*   [Deprecated](#deprecated)
*   [Miscellaneous](#Miscellaneous)
    *   [Contributing](#contributing)
    *   [Code of Conduct](#code-of-conduct)
    *   [License](#license)

## General information

*   [Survey of screenshot-based CSS testing tools](https://gist.github.com/cvrebert/adf91e429906a4d746cd)
*   [Wikipedia: Regression testing](https://en.wikipedia.org/wiki/Regression_testing)

## Browser automation

*   [Cypress.io](https://www.cypress.io/) - An automation framework that runs in-browser.
*   [Selenium (⭐31k)](https://github.com/SeleniumHQ/selenium) - Browser automation framework and ecosystem.
*   [SlimerJS (⭐3k)](https://github.com/laurentj/slimerjs) - Scriptable browser like PhantomJS, based on Firefox.
*   [Webdriver.io (⭐9.1k)](https://github.com/webdriverio/webdriverio/) - Node.js bindings implementation for the W3C WebDriver protocol.

## Tools and frameworks (a-z↓)

*   [AET (⭐148)](https://github.com/Cognifide/aet) - Scalable testing tool providing visual regression testing, accessibility and performance validation, markup analysis and more.
*   [AyeSpy (⭐207)](https://github.com/newsuk/ayespy) - 44 image comparisons in 90 seconds.
*   [BackstopJS (⭐6.9k)](https://github.com/garris/BackstopJS) - Config-driven automated screenshot test framework.
*   [basset](https://basset.io) - Open source platform for generating and reviewing visual differences. Supports multiple browsers, integrations for github and slack.
*   [Chimp (⭐799)](https://github.com/xolvio/chimp) - Develop acceptance tests & end-to-end tests with realtime feedback.
*   [CodeceptJS (⭐4.1k)](https://github.com/codeception/codeceptjs/) - Modern Era Acceptance Testing Framework for NodeJS.
*   [Creevey (⭐391)](https://github.com/wKich/creevey) - Cross-browser visual testing with magic. Feature-rich tool with UI Runner, Tests Hot Reloading, Docker and Storybook integration.
*   [CSSCritic (⭐487)](https://github.com/cburgmer/csscritic) - Lightweight CSS regression testing.
*   [Differencify (⭐634)](https://github.com/NimaSoroush/differencify) - A library for visual regression testing using [Puppeteer (⭐89k)](https://github.com/GoogleChrome/puppeteer).
*   [ember-visual-test (⭐25)](https://github.com/Cropster/ember-visual-test) - Simple visual regression testing for [Ember](https://emberjs.com/).
*   [FuncUnit (⭐572)](https://github.com/bitovi/funcunit) - A functional test suite based on jQuery
*   [Galen (⭐1.4k)](https://github.com/galenframework/galen) - Java framework based on [Selenium (⭐31k)](https://github.com/SeleniumHQ/selenium).
*   [gatling (⭐56)](https://github.com/gabrielrotbart/gatling) - Integrated visual RSpec matcher which makes real visual testing easy (Ruby).
*   [grunt-photobox (⭐278)](https://github.com/stefanjudis/grunt-photobox) - Plugin to prevent your project of broken layout via screenshot photo sessions of your site.
*   [Happo (⭐199)](https://github.com/happo/happo.io) - Visual diffing in CI for user interfaces.
*   [Hardy (⭐323)](https://github.com/thingsinjars/Hardy) - Selenium-driven, cucumber-powered CSS testing.
*   [jest-image-snapshot (⭐3.9k)](https://github.com/americanexpress/jest-image-snapshot) - Jest matcher that performs image comparisons using [pixelmatch](https://www.npmjs.com/package/pixelmatch)
*   [jest-puppeteer-react (⭐72)](https://github.com/Hapag-Lloyd/jest-puppeteer-react) - Visual regression testing with Jest and puppeteer for React components
*   [Karma](http://karma-runner.github.io/latest/index.html) - A test runner by the AngularJS team, that fits all our needs.
*   [Loki (⭐1.8k)](https://github.com/oblador/loki) - Visual regression testing for Storybook using Chrome in docker et al.
*   [Look-alike (⭐34)](https://github.com/kdzwinel/Look-alike) - Chrome Extension for taking and comparing screenshots.
*   [Lost Pixel (⭐1.4k)](https://github.com/lost-pixel/lost-pixel) - Holistic visual regression testing for full pages, components (via Storybook and Ladle integration), and custom shots (e.g. via Cypress).
*   [Muppeteer (⭐66)](https://github.com/HuddleEng/Muppeteer) - Visual regression testing framework for Chrome using [Mocha](https://mochajs.org/) and [Puppeteer (⭐89k)](https://github.com/GoogleChrome/puppeteer).
*   [Needle (⭐592)](https://github.com/python-needle/needle) - Needle is a tool for testing visuals with Selenium and nose (Python).
*   [Nightmare (⭐20k)](https://github.com/segmentio/nightmare) - High-level browser automation library based on Electron.
*   [Nightwatch (⭐12k)](https://github.com/nightwatchjs/nightwatch) - Automated testing and continuous integration framework based on Node.js and using the Webdriver protocol.
*   [OSnap (⭐157)](https://github.com/eWert-Online/osnap) - The speedy and easy to use Snapshot Testing tool for your project (1200 snapshots will run in under 3 minutes).
*   [Playwright (⭐68k)](https://github.com/microsoft/playwright) - Node library to automate Chromium, Firefox and WebKit with a single API.
*   [Protractor (⭐8.7k)](https://github.com/angular/protractor) - E2E test framework for Angular apps.
*   [Puppeteer (⭐89k)](https://github.com/GoogleChrome/puppeteer) - Headless Google Chrome Node API.
*   [qd\_screenshottests](https://www.drupal.org/project/qd_screenshottests) - CasperJS-based UI regression and functional testing focused on Drupal 8 sites.
*   [reg-cli (⭐362)](https://github.com/bokuweb/reg-cli) - Visual regression test tool which output easy-to-read single file html report.
*   [reg-suit (⭐1.2k)](https://github.com/reg-viz/reg-suit) - Visual regression testing suite which compares images, stores snapshots, and notifies the difference to your GitHub repo.
*   [ResembleJS (⭐4.5k)](https://github.com/Huddle/Resemble.js) - Analyse and compare images with Javascript and HTML5.
*   [Selenide (⭐1.9k)](https://github.com/selenide/selenide) - Framework powered by Selenium WebDriver for writing easy-to-read and easy-to-maintain automated tests in Java.
*   [Shoov (⭐39)](https://github.com/shoov/shoov) - UI regression and functional testing focused on Drupal 7 sites.
*   [Spectre (⭐461)](https://github.com/wearefriday/spectre) - Provides image comparison capabilities and an admin interface for managing screenshots.
*   [test-crawler (⭐33)](https://github.com/apiel/test-crawler) - Visual regression testing, by crawling a website and providing snapshot comparison reports.
*   [TestCafe (⭐9.8k)](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
*   [Touca (⭐501)](https://github.com/trytouca/trytouca) - Open source continuous regression testing without the hassle of managing snapshot files.
*   [vrtest (⭐15)](https://github.com/nathanmarks/vrtest) - JavaScript library for running visual regression tests on your components cross browser via selenium.
*   [wdio-visual-regression (⭐3)](https://github.com/ennjin/wdio-visual-regression) - Visual regression tool for webdriver.io
*   [Wendigo (⭐150)](https://github.com/angrykoala/wendigo) - Test-oriented browser automation library based on Puppeteer.
*   [Wraith (⭐4.8k)](https://github.com/BBC-News/wraith) - Easy to use ruby tool with docker support.
*   [Zombie.js](http://zombie.js.org/) - Insanely fast, headless full-stack testing using Node.js.

## Online services (a-z↓)

*   [applitools](https://applitools.com) - Cloud base visual tests.
*   [Argos](https://argos-ci.com) - The open source visual testing platform for modern engineering teams.
*   [Axcept](https://axcept.io) - Testing for the whole team. Up to 100 tests in parallel. Endpoint Mocking. Code Coverage.
*   [Browser Shots](http://browsershots.org) - Screenshots only.
*   [browserling](https://www.browserling.com) - LIVE interactive cross-browser testing.
*   [BrowserStack](https://www.browserstack.com) - Free for Open Source. Supports [Selenium Webdriver (⭐31k)](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
*   [BugBug.io](https://bugbug.io/) - Lightweight test automation tool for web applications. Easy to learn and doesn't require coding. It's free, with unlimited tests. For an additional monthly fee, you also get cloud monitoring and CI/CD integration.
*   [Chromatic](https://www.chromatic.com/) - Visual testing and UI review for component libraries. Cloud-based. [Video](https://youtu.be/6KDLJBcutQE)
*   [CrossBrowserTesting](https://crossbrowsertesting.com) - Manual & exploratory testing on 1500+ real browsers and mobile devices.
*   [Diffy](https://diffy.website) - Cloud based visual regression tool that focuses on Drupal and WordPress. Full page screenshots and minimal number of false positives. Just provide URLs of your sites to get started. No coding required.
*   [Fluxguard](https://fluxguard.com) - Screenshot pixel and DOM change comparisons and regressions.
*   [Ghost Inspector](https://ghostinspector.com) - See [introduction video](https://vimeo.com/ghostinspector/intro).
*   [Happo](https://happo.io/) - Cloud-based screenshot testing service with support for multiple browsers.
*   [HeadSpin](https://www.headspin.io/) - HeadSpin's Regression testing gives you a powerful comparison tool for analysing degradation across new app builds, OS releases, feature additions, locations, and more.
*   [LambdaTest](https://www.lambdatest.com/) - Perform Automated and Live Interactive Cross Browser Testing on 2000+ Real Browsers and Operating Systems Online.
*   [Meticulous.ai](https://meticulous.ai) - Easily create frontend tests without writing code. Use Meticulous to record workflows on your web app. You can then replay those flows on new frontend code, and create a test by diffing two replays.
*   [Micoo (⭐191)](https://github.com/Mikuu/Micoo) - Open source service for all UI application visual regression solution
*   [percy.io](https://percy.io) - Continuous visual reviews for web apps.
*   [Pixeleye](https://pixeleye.io/home) - Open-source, multi-browser visual review and testing platform with the option to self-host. It has first-class support for Storybook, Cypress, Playwright & Puppeteer.
*   [Preflight: Cypress Recorder](https://cypress.preflight.com) - Create AI-powered Cypress Tests/POM models in your browser and automate Email & Visual testing for Cypress.
*   [Preflight](https://preflight.com) - Easiest Visual regression testing and Automated Web Testing tool. (Limited) free use.
*   [Reflect](https://reflect.run) - Visual regression testing and test automation tool.
*   [screener.io](https://screener.io) - For React, looks open source.
*   [screenster.io](http://screenster.io) - Cloud based automation testing platform for web and mobile UI.
*   [TestGrid](https://www.testgrid.io/) - Perform End to End test automation be it cross browser testing, mobile app testing, performance testing or API testing on cloud or on-premise.
*   [TestingBot](https://testingbot.com) - Provides +3600 browsers to run automated visual tests. Free for Open Source.
*   [Testomat.io Reporter (⭐132)](https://github.com/testomatio/reporter) - Allows to collect tests to a Test Case Management System (TCMS) like testomat.io and sync manual and automated tests in one place.
*   [testRigor](https://testrigor.com) - E2E functional test automation tool for web, mobile, and desktop tests.
*   [Vidiff](https://vidiff.com) - Cloud-based visual regression testing across stages.
*   [Visual Knight](https://visual-knight.io/) - Cloud-based visual testing platform with realtime results for testing tools.
*   [Visual Regression Tracker (⭐612)](https://github.com/Visual-Regression-Tracker/Visual-Regression-Tracker) - Open Source selfhosted service for visual regression testing
*   [VisWiz.io](https://www.viswiz.io) - Flexible visual regression testing service.
*   [VRTs - Visual Regression Tests](https://bleech.de/en/products/visual-regression-tests/) – WordPress plugin auto-updating screenshots on content updates, preventing false positives.

## Blog posts  (a-z↓)

*   [Angela Riggs: Visual Regression Testing with BackstopJS](https://www.metaltoad.com/blog/visual-regression-testing-backstopjs) - Tutorial using BackstopJS.
*   [Automated screenshot comparison tests with headless Chrome, Puppeteer and Pixelmatch, in Bitbucket pipeline](https://jakobzanker.de/blog/automated-screenshot-comparison-test-with-headless-chrome-in-bitbucket-pipeline/)
*   [Automatic visual diffing with Puppeteer](https://meowni.ca/posts/2017-puppeteer-tests/)
*   [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Headless Chrome is shaking up traditional approaches to test automation.
*   [Everything you need to know about Visual Regression Testing in 2022](https://david-x.medium.com/the-state-of-visual-regression-testing-in-2022-5de10ffe8f6f) - Intro to visual regression testing with tools updated as of 2022.
*   [Garris Shipon: Automating CSS Regression Testing](https://css-tricks.com/automating-css-regression-testing/) - Tutorial using BackstopJS.
*   [Garris Shipon: Visual Regression Testing For Angular Applications](https://davidwalsh.name/visual-regression-testing-angular-applications) -  Tutorial using BackstopJS.
*   [Keeping a React Design System consistent: using visual regression testing to save time and headaches](https://techblog.commercetools.com/keeping-a-react-design-system-consistent-f055160d5166) - Using percy, and jest puppeteer to visually test a React component library.
*   [Kevin Lamping: The 5 best visual regression testing tools](http://www.creativebloq.com/features/the-5-best-visual-regression-testing-tools) - Compares: Wraith, PhantomCSS, Gemini, WebdriverCSS and Spectre.
*   [Make visual regression testing easier](https://medium.com/@nima.soroush.h/make-visual-regression-testing-easier-4a3dc7073737) - Introduction to [Differencify (⭐634)](https://github.com/NimaSoroush/differencify) and how to use it.
*   [Pavels Jelisejevs: Visual Regression Testing with PhantomCSS](https://www.sitepoint.com/visual-regression-testing-with-phantomcss) - Introduction to PhantomCSS.
*   [Phillip Gourley: Making visual regression useful](https://medium.com/@philgourley/making-visual-regression-useful-acfae27e5031) - Why you should use BackstopJS.
*   [Poor man's visual regression testing](https://idkshite.com/posts/compare-visual-changes) - Improved manual visual regression testing with the PerfectPixel chrome plugin.
*   [theheadless.dev](https://theheadless.dev) - Blog with practical guides and runnable examples on Playwright and Puppeteer.
*   [UI Visual Regression Testing with Micoo](https://mikuu.medium.com/ui-visual-regression-testing-with-micoo-12c7a4a036b9) - Introduction about how to do visual regression testing with Micoo service
*   [Visual Regression Test with WebdriverIO & WebdriverCSS](https://medium.com/@dalenguyen/visual-regression-test-with-webdriverio-webdrivercss-d7675a1812b2) - Tutorial using WebdriverIO and WebdriverCSS with Spec Reporter
*   [Visual regression testing for Hugo with Github-CI and BackstopJS](https://jameskiefer.com/posts/visual-regression-testing-for-hugo-with-github-ci-and-backstopjs/) - How to automate regression testing for Hugo with BackstopJS
*   [Visual regression testing using Jest, Chromeless and AWS Lambda (⭐17)](https://github.com/novemberfiveco/visual-regression-testing-jest-chromeless) - Tutorial using Chromeless and jest-image-snapshot.
*   [Visual Regression Testing with Puppeteer & Jest](https://www.viswiz.io/help/tutorials/puppeteer) - Tutorial to setup visual testing with Puppeteer, Jest and VisWiz.io.

## Slideshows, talks and videos  (a-z↓)

*   [CSS Regression Testing with Wraith](https://youtu.be/gE_19L0l2q0) - Screencast: Basic introduction to wraith, a screenshot comparison tool.
*   [Cypress in 100 Seconds](https://www.youtube.com/watch?v=BQqzfHQkREo\&ab_channel=Fireship) - Introduction video by Fireship.
*   [Look-alike - visual regression testing tool](https://youtu.be/vTyoQuC0To8) - Demo what the Look-alike Chrome extension is, how it works and how and why it was build.
*   [Screencast on CSS critic - a lightweight testing framework for CSS](https://youtu.be/AqQ2bNPtF60) - How to write your first CSS test with CSS critic, make it pass, break it, and make it pass again.
*   [Screenster Tutorial](https://youtu.be/Zy8y_dGzZXI) - Tutorial on how to create visual automated tests with Screenster.
*   [Visual Regression Testing - from a tool to a process](https://speakerdeck.com/nikhilverma/visual-regression-testing-from-a-tool-to-a-process) by Nikhil Verma - How the Mobile Web team in Badoo converted and integrated PhantomCSS into their workflow and connected it to their CI process.
*   [Visual Regression Testing with PhantomCSS](https://youtu.be/Vp8vnXMjIfw) - Talk by Jon Bellah on how to use PhantomCSS during wordpress development.
*   [Visual Regression Testing with Shoov](https://youtu.be/CBBiJ6YlXLc) - How to setup shoov and get your first test written.
*   [Visual Regression Testing: Sanity Checks With BackstopJS](https://youtu.be/l8lGj8Zh0k4) - Screencast with code demo and best practices.

## Deprecated  (a-z↓)

The following projects are no longer maintained actively but are still worth mentioning because of their user base.

*   [CasperJS (⭐7.2k)](https://github.com/casperjs/casperjs) - Navigation scripting and testing utility for PhantomJS and SlimerJS. (archived 2018)
*   [Chromeless (⭐13k)](https://github.com/graphcool/chromeless) - Chrome automation made simple. Runs locally or headless on AWS Lambda. (archived 2018)
*   [DalekJS (⭐695)](https://github.com/dalekjs/dalek) - Automated cross browser testing with JavaScript. No longer maintained since 4 Jun 2017.
*   [dpxdt (⭐1.4k)](https://github.com/bslatkin/dpxdt) - End-to-end testing with Python.
*   [Gemini (⭐1.5k)](https://github.com/gemini-testing/gemini) - Feature rich framework with support for [Selenium (⭐31k)](https://github.com/SeleniumHQ/selenium) and  [CasperJS (⭐7.2k)](https://github.com/casperjs/casperjs). Gemini is deprecated, use hermione instead.
*   [Huxley (⭐4.1k)](https://github.com/facebookarchive/huxley) - Python framework based on [Selenium Webdriver (⭐31k)](https://github.com/SeleniumHQ/selenium/tree/master/javascript/node/selenium-webdriver).
*   [Navalia (⭐962)](https://github.com/joelgriffith/navalia) - Browser Automation based on headless Chrome and GraphQL. (archived 2018)
*   [OcularJS (⭐7)](https://github.com/mmacartney10/ocularjs) - uses [PhantomJS (⭐29k)](https://github.com/ariya/phantomjs).
*   [PhantomCSS](https://github.com/Huddle/PhantomCSS) - Visual/CSS regression testing with PhantomJS or SlimerJS. No longer maintained since 22 Dec 2017.
*   [PhantomFlow](https://github.com/Huddle/PhantomFlow) - Experimental approach to UI testing, based on Decision Trees.
*   [PhantomJS (⭐29k)](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit. No longer maintained since 2 June 2018.
*   [trifleJS (⭐825)](https://github.com/sdesalas/trifleJS) - Headless automation for Internet Explorer. (last update 2016)
*   [Visual Review (⭐275)](https://github.com/xebia/VisualReview) - A human-friendly tool for testing and reviewing visual regressions.
*   [WebdriverCSS (⭐613)](https://github.com/webdriverio/webdrivercss) - WebdriverCSS sits on top of [Webdriver.io (⭐9.1k)](https://github.com/webdriverio/webdriverio/) and hooks into [Selenium (⭐31k)](https://github.com/SeleniumHQ/selenium).

## Miscellaneous

### Contributing

See the [Contribution Guide](https://github.com/mojoaxel/awesome-regression-testing/blob/master/README.md/.github/CONTRIBUTING.md) for details on how to contribute.

### Code of Conduct

See the [Code of Conduct](https://github.com/mojoaxel/awesome-regression-testing/blob/master/README.md/.github/CODE-OF-CONDUCT.md) for details. Basically it comes down to:

> In the interest of fostering an open and welcoming environment, we as
> contributors and maintainers pledge to making participation in our project and
> our community a harassment-free experience for everyone, regardless of age, body
> size, disability, ethnicity, gender identity and expression, level of experience,
> nationality, personal appearance, race, religion, or sexual identity and orientation.

### License

[![CC-BY-SA](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
License holders are [all contributors (⭐2.2k)](https://github.com/mojoaxel/awesome-regression-testing/graphs/contributors).

